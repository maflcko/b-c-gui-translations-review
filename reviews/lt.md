# Translations Review by LLM (✨ experimental)

The review quality depends on the LLM and the language. Currently, a fast LLM without rate limits is used. If you are interested in better quality for a specific language, please file an issue to ask for it to be re-run with a stronger model.



<details><summary>lt</summary>

[If the result is of low quality, please file an issue to find a better LLM for this language.](../../issues/new?title=%5Blt%5D%20low%20quality)


```
        <source>There was an error trying to save the address list to %1. Please try again.</source>
        <extracomment>An error message. %1 is a stand-in argument for the name of the file we attempted to save to.</extracomment>
        <translation>Bandant išsaugoti adresų sąrašą - įvyko klaida keliant į %1. Prašome bandyti dar kartą.</translation>
    
YES  
The phrase "įvyko klaida keliant į %1" is incorrect and awkward in Lithuanian. The verb "kelti" (to raise/lift) is not appropriate for this context. The correct verb for saving a file is "išsaugoti" or "rašyti". Also, the dash after "adresų sąrašą" is unnecessary and breaks the sentence flow.

Correct translation:  
"Bandant išsaugoti adresų sąrašą %1 įvyko klaida. Prašome bandyti dar kartą."
```

```
        <source>Enter the old passphrase and new passphrase for the wallet.</source>
        <translation>Įveskite seną ir naują slaptažodį.</translation>
    
YES  
The translation is incomplete and less precise. The English source specifically mentions "passphrase" and "for the wallet," while the translation uses a generic term "slaptažodį" (password) instead of "slaptafrazė" (passphrase) and omits "for the wallet." The nuance is important in the Bitcoin context.

Correct translation:  
Įveskite senuosius ir naujus slaptafrazę piniginei.  

Alternatively, to be more natural:  
Įveskite seną ir naują slaptafrazę piniginei.
```

```
        <source>Remember that encrypting your wallet cannot fully protect your bitcoins from being stolen by malware infecting your computer.</source>
        <translation>Atminkite kad piniginės užšifravimas neužtrikrina kad jūsų bitkoinai negali būti pavogti dėl kenkėjiškų programų užkrėtusių jūsų kompiuterį.</translation>
    
YES  
The Lithuanian translation contains errors and awkward phrasing. Specifically:  
- "neužtrikrina" is not a correct word; likely intended "neužtikrina" (does not guarantee).  
- The phrase "kad jūsų bitkoinai negali būti pavogti" translates as "that your bitcoins cannot be stolen," which contradicts the source meaning. The source says encryption "cannot fully protect" bitcoins from being stolen, implying a risk remains. The translation implies bitcoins cannot be stolen, which is incorrect.  
- The structure is awkward and difficult to understand.

Correct translation:  
"Atminkite, kad piniginės užšifravimas negali visiškai apsaugoti jūsų bitkoinų nuo vagystės dėl kenkėjiškų programų, kurios gali užkrėsti jūsų kompiuterį."
```

```
        <source>Load Partially Signed Bitcoin Transaction from clipboard</source>
        <translation>Užkraukite dalinai pasirašytas Bitcoin transakcijas iš iškarpinės...</translation>
    
YES  
The source refers to loading a single "Partially Signed Bitcoin Transaction" (singular), but the translation uses the plural form "dalinai pasirašytas Bitcoin transakcijas" (transactions), which is incorrect. Additionally, the translation adds "..." at the end, which is not present in the source and may be misleading or unnecessary.

Correct translation:  
Užkraukite dalinai pasirašytą Bitcoin transakciją iš iškarpinės
```

```
        <source>Type: %1
</source>
        <translation>Spausti: %1
</translation>
    
YES  
The English word "Type" refers to a category or kind, especially in the context of Bitcoin (e.g., address type). The Lithuanian translation "Spausti" means "Press" or "Click," which is incorrect here. The correct Lithuanian translation for "Type" in this context is "Tipas."

Correct translation:  
Spausdinimas: %1  
or more accurately simply:  
Tipas: %1
```

```
        <source>Label: %1
</source>
        <translation>Antraštė: %1
</translation>
    
YES  
The translation "Antraštė" is Lithuanian for "headline" or "title," not "label" in the sense of a tag or descriptor as used in Bitcoin context. The correct Lithuanian word for "Label" (a tag or descriptor) is "Žymė."

Correct translation:  
Žymė: %1
```

```
        <source>Copy change</source>
        <translation>Kopijuoti keisti</translation>
    
YES  
The translation "Kopijuoti keisti" incorrectly translates the phrase. In the Bitcoin context, "change" refers to the leftover amount returned in a transaction, not the verb "to change." Here, "Copy change" means "copy the change amount," so "change" should be a noun. The correct Lithuanian translation should use a noun form for "change," for example:  

Correct translation:  
Kopijuoti grąžą
```

```
        <source>change from %1 (%2)</source>
        <translation>pakeisti nuo %1 (%2)</translation>
    
YES  
The translation "pakeisti nuo %1 (%2)" is incorrect in this context. In Bitcoin terminology, "change" refers to the leftover money returned to the sender after a transaction, not the verb "to change." The correct Lithuanian translation should reflect the noun "change" as in "change from %1 (%2)," meaning the change amount from an address or transaction.

Correct translation:  
"grąža iš %1 (%2)"  

Alternatively, a more contextual phrase might be:  
"grąža nuo %1 (%2)"  

Both "grąža" (change/return) and the preposition "iš" or "nuo" ("from") properly convey the meaning in context.
```

```
        <source>Disable Private Keys</source>
        <translation>Atjungti Privačius Raktus</translation>
    
YES  
The Lithuanian translation has incorrect capitalization. In Lithuanian, only the first word and proper nouns are capitalized in titles or phrases like this. Also, "Atjungti" (meaning "to disconnect") is not the best verb choice for "Disable" in this context. A better word for "Disable" would be "Išjungti" or "Deaktyvuoti."  

Correct translation:  
Išjungti privačius raktus
```

```
        <source>Number of script verification threads</source>
        <translation>Patvirtinimų skaičius</translation>
    
YES  
The translation "Patvirtinimų skaičius" means "Number of verifications," which is incomplete and does not convey that it specifically refers to "script verification threads." The original English phrase specifies the number of threads dedicated to verifying scripts, so the translation should reflect this.  

Correct translation:  
"Skriptų patikros gijų skaičius"
```

```
        <source>Prune block storage to</source>
        <translation>blokuokite saugyklą į</translation>
    
YES  
The translation is inaccurate and somewhat awkward. The English phrase "Prune block storage to" is a technical instruction referring to reducing/block pruning the storage used for blocks. The Lithuanian verb "blokuokite" means "block" in the sense of "to block or prevent," which is incorrect here. The correct translation should use a verb related to pruning or trimming storage.

Correct translation:  
"Sutrumpinkite bloko saugyklą iki"
```

```
        <source>Port of the proxy (e.g. 9050)</source>
        <translation>Tarpinio serverio preivadas (pvz, 9050)</translation>
    
YES  
The Lithuanian word "preivadas" is misspelled. The correct word is "prievadas". Also, there should be a period after "pvz" (abbreviation for "pavyzdžiui"). The comma should be replaced with a period.  

Correct translation:  
Tarpinio serverio prievadas (pvz. 9050)
```

```
        <source>Minimize to the tray instead of the taskbar</source>
        <translation>M sumažinti langą bet ne užduočių juostą</translation>
    
YES  
The translation is incorrect and incomplete. The English phrase "Minimize to the tray instead of the taskbar" means that the application should minimize to the system tray rather than the taskbar. The provided translation "M sumažinti langą bet ne užduočių juostą" is incomplete ("M" at the beginning is likely a typo or stray character), and it literally means "To reduce the window but not the taskbar," which is inaccurate and awkward.  

Correct translation:  
"Minimizuoti į dėklą, o ne į užduočių juostą"
```

```
        <source>Choose the default subdivision unit to show in the interface and when sending coins.</source>
        <translation>Rodomų ir siunčiamų monetų kiekio matavimo vienetai</translation>
    
YES  
The translation is incomplete and inaccurate. It translates to "Units of measurement for amounts of received and sent coins," which does not convey the instruction to "Choose the default subdivision unit to show in the interface and when sending coins."

Correct translation:  
Pasirinkite numatytąją dalinimo vienetą, kuris bus rodomas sąsajoje ir siunčiant monetas.
```

```
        <source>Your current balance in watch-only addresses</source>
        <translation>Jūsų dabartinis balansas tik stebimų adresų</translation>
    
YES
The translation uses Lithuanian ("Jūsų dabartinis balansas tik stebimų adresų"), but 'lt' stands for Lithuanian, and the text is actually in Lithuanian. However, Lithuanian translation is incorrect in grammar and form.

1. "Jūsų" means "your", which is correct.
2. "dabartinis balansas" means "current balance", correct.
3. "tik stebimų adresų" literally translates as "only (of) watched addresses", but in Lithuanian the phrasing is awkward and incomplete. It misses a preposition or additional words to connect properly.

A better Lithuanian translation would directly translate "Your current balance in watch-only addresses" as:

"Jūsų dabartinis likutis tik stebimų adresų sąskaitose"

("likutis" is often used for "balance" in financial contexts; "adresas" is the direct translation for address but commonly, "sąskaita" (account) or "adresai" is used in Bitcoin wallet contexts.)

Alternatively, to keep it closer:

"Jūsų dabartinis balansas tik stebimų adresų sąskaitose"

This means: "Your current balance in watch-only addresses' accounts." This is more idiomatic.

Also, the original translation lacks a preposition like "in" between "balance" and "addresses".

Correct translation:

Jūsų dabartinis balansas tik stebimų adresų sąskaitose
```

```
        <source>Cannot start bitcoin: click-to-pay handler</source>
        <translation>Negalima paleisti bitcoin: paspauskite sumokėti tvarkytojui</translation>
    
YES  
The translation is inaccurate and somewhat misleading. The English phrase refers to the inability to start the "click-to-pay handler" related to Bitcoin. The current translation "paspauskite sumokėti tvarkytojui" means "click to pay to the handler," which does not convey the intended meaning.

A better translation would be:  
"Negalima paleisti bitcoin: „click-to-pay“ tvarkyklės"  
or  
"Negalima paleisti bitcoin: paspauskite mokėti tvarkyklės"  

However, since "click-to-pay" is a technical term, it is often better to keep it untranslated or in quotes and translate "handler" as "tvarkyklė" (handler). Also "bitcoin" should be capitalized as "Bitcoin".

Correct translation:  
Negalima paleisti Bitcoin: „click-to-pay“ tvarkyklės
```

```
        <source>'bitcoin://' is not a valid URI. Use 'bitcoin:' instead.</source>
        <translation>„bitcoin: //“ nėra galiojantis URI. Vietoj to naudokite „bitcoin:“.</translation>
    
YES
There should be no spaces around the slashes in the URL scheme 'bitcoin://'. The source text correctly uses 'bitcoin://', but the translation shows it as 'bitcoin: //', which is incorrect and changes the meaning. The format specifiers are not applicable here.

Correct translation:
„bitcoin://“ nėra galiojantis URI. Vietoj to naudokite „bitcoin:“.
```

```
        <source>Custom change address</source>
        <translation>Pakeisti adresą</translation>
    
YES  
The original source "Custom change address" refers to a specific Bitcoin wallet or P2P network address for the 'change' output in a transaction. The Lithuanian translation "Pakeisti adresą" means "Change address" in the sense of a command (imperative) "Change the address," which is incorrect here. The translation should reflect the noun phrase "Custom change address."  

Correct translation:  
"Individualizuotas keitimo adresas"  
or  
"Tinkintas keitimo adresas"
```

```
        <source>Using the fallbackfee can result in sending a transaction that will take several hours or days (or never) to confirm. Consider choosing your fee manually or wait until you have validated the complete chain.</source>
        <translation>Naudojant backbackfee gali būti siunčiamas sandoris, kuris užtruks kelias valandas ar dienas (arba niekada), kad patvirtintų. Apsvarstykite galimybę pasirinkti mokestį rankiniu būdu arba palaukite, kol patvirtinsite visą grandinę.</translation>
    
YES
The term "backbackfee" in the translation is incorrect and looks like a typographical error or mistranslation of "fallbackfee." Additionally, the phrase "kad patvirtintų" is incorrect in this context; it should reflect that the transaction will take time to be confirmed (i.e., passive voice, "kad bus patvirtintas"). Also, the polite imperative form "apsvarstykite galimybę" is somewhat awkward here; a better phrasing would be more natural in Lithuanian.

Correct translation:
Naudojant fallbackfee gali būti išsiųstas sandoris, kurio patvirtinimas užtruks kelias valandas ar dienas (arba niekada). Apsvarstykite galimybę pasirinkti mokestį rankiniu būdu arba palaukite, kol bus patvirtinta visa grandinė.
```

```
        <source>Add Recipient</source>
        <translation>A Pridėti gavėją</translation>
    
YES  
The translation contains an unnecessary and incorrect leading "A". The correct translation for "Add Recipient" in Lithuanian is simply "Pridėti gavėją".

Correct translation:  
Pridėti gavėją
```

```
        <source>Enable Replace-By-Fee</source>
        <translation>Įgalinti keitimąsi mokesčiu</translation>
    
YES  
The translation is in Lithuanian ("Įgalinti keitimąsi mokesčiu"), but it contains a Polish character "Į" instead of the correct Lithuanian "Į" (note: "Į" is used in Lithuanian, but the phrase meaning "Enable Replace-By-Fee" is not fully correct). More importantly, the phrase "keitimąsi mokesčiu" translates roughly as "exchange with fee," which is not an accurate or natural way to express the Bitcoin term "Replace-By-Fee."

A more accurate Lithuanian translation, common in Bitcoin context, is:

Įgalinti mokesčio pakeitimą

("Enable fee replacement" or "Enable Replace-By-Fee")

Correct translation:  
<translation>Įgalinti mokesčio pakeitimą</translation>
```

```
        <source>With Replace-By-Fee (BIP-125) you can increase a transaction's fee after it is sent. Without this, a higher fee may be recommended to compensate for increased transaction delay risk.</source>
        <translation>Naudojant Replace-by-Fend (BIP-125) galite išsiųsti sandorio mokestį vėliau. Be jo, gali būti rekomenduojamas didesnis mokestis, kad būtų kompensuota padidėjusi sandorio vėlavimo rizika.</translation>
    
YES  
The term "Replace-By-Fee" is mistranslated as "Replace-by-Fend" ("Fend" is incorrect). The correct phrase is "Replace-By-Fee" (or the Lithuanian equivalent if any established term exists). Also, "išsiųsti sandorio mokestį vėliau" ("send the transaction fee later") is inaccurate; the English means "increase a transaction's fee after it is sent," not "send it later."

A better translation would be:  
"Naudodami Replace-By-Fee (BIP-125) galite padidinti sandorio mokestį po to, kai sandoris jau išsiųstas. Be to, gali būti rekomenduojamas didesnis mokestis, kad kompensuotumėte padidėjusią sandorio vėlavimo riziką."
```

```
        <source>Copy change</source>
        <translation>Kopijuoti keisti</translation>
    
YES  
The translation "Kopijuoti keisti" incorrectly translates the phrase. In the Bitcoin context, "change" refers to the leftover amount returned in a transaction, not the verb "to change." Here, "Copy change" means "copy the change amount," so "change" should be a noun. The correct Lithuanian translation should use a noun form for "change," for example:  

Correct translation:  
Kopijuoti grąžą
```

```
        <source>Duplicate address found: addresses should only be used once each.</source>
        <translation>Rastas dublikatas: adresai turėtų būti naudojami tik vieną kartą.</translation>
    
YES  
The Lithuanian translation contains an error in the noun form and the verb agreement. The source phrase "Duplicate address found" implies a single duplicate address, so "dublikatas" is fine, but the phrase "adresai turėtų būti naudojami tik vieną kartą" uses "adresai" (plural), which conflicts with the singular "dublikatas." It should be singular "adresas" to match "dublikatas." Also, the verb "turėtų būti naudojami" (plural form) should be singular "turėtų būti naudojamas" to agree with the singular noun "adresas."

Correct translation:  
Rastas dublikatas: adresas turėtų būti naudojamas tik vieną kartą.
```

```
        <source>Paste address from clipboard</source>
        <translation>Įvesti adresą iš mainų atminties</translation>
    
YES  
The translation "Įvesti adresą iš mainų atminties" means "Enter address from clipboard," which is inaccurate because "Paste" implies inserting the copied content, not manually entering it. A better translation that correctly conveys "Paste address from clipboard" would be:  
Įklijuoti adresą iš mainų atminties
```

```
        <source>The Bitcoin address to sign the message with</source>
        <translation>Bitcoin adresas, kuriuo bus pasirašytas pranešimas su</translation>
    
YES  
The Lithuanian translation has incorrect word order and an awkward ending "su" ("with") placed at the end, which is not natural in Lithuanian. The English phrase "The Bitcoin address to sign the message with" means "Bitcoin address that will be used to sign the message," so "su" should precede "pranešimas" and the sentence structure should be corrected for clarity and grammar.

Correct translation:  
Bitcoin adresas, kuriuo bus pasirašytas pranešimas
```

```
        <source>Paste address from clipboard</source>
        <translation>Įvesti adresą iš mainų atminties</translation>
    
YES  
The translation "Įvesti adresą iš mainų atminties" means "Enter address from clipboard," which is inaccurate because "Paste" implies inserting the copied content, not manually entering it. A better translation that correctly conveys "Paste address from clipboard" would be:  
Įklijuoti adresą iš mainų atminties
```

```
        <source>Sign the message to prove you own this Bitcoin address</source>
        <translation>Registruotis žinute įrodymuii, kad turite šį adresą</translation>
    
YES  
The Lithuanian translation contains several issues:  
- "Registruotis" means "to register" or "to sign up," which is incorrect here. The correct verb is "Pasirašyti" (to sign).  
- "žinute" should be in the instrumental case: "žinute" → "žinute" (correct form is "žinute" instrumental, but note that in Lithuanian "žinutę" (accusative) is usually used after "pasirašyti," so better to say "žinutę").  
- "įrodymuii" is misspelled; extra 'i' at the end and the word order is awkward. The phrase should be "įrodant, kad" (meaning "to prove that").  
- The phrase "kad turite šį adresą" is too generic; it should specify "Bitcoin adresą" to match the source.  

Correct translation:  
"Pasirašykite žinutę, kad įrodytumėte, jog esate šio Bitcoin adreso savininkas"  

Alternatively shorter:  
"Pasirašykite žinutę, kad įrodytumėte, jog turite šį Bitcoin adresą"  

Full corrected version:  
<translation>Pasirašykite žinutę, kad įrodytumėte, jog turite šį Bitcoin adresą</translation>
```

```
        <source>The signature did not match the message digest.</source>
        <translation>Parašas neatitinka žinutės.</translation>
    
YES  
The translation "Parašas neatitinka žinutės." is incomplete and inaccurate. The source sentence means "The signature did not match the message digest." The phrase "message digest" refers to a cryptographic hash of the message, which should be preserved in translation. The given translation omits "digest" ("santrauka" or "apibendrinimas") and simplifies "did not match" to present tense "neatitinka" ("does not match") instead of past tense "neišėjo atitikti" or similar.  

A better translation would be:  
"Parašas nesutapo su žinutės santrauka."  
or  
"Parašas nesutapo su žinutės apibendrinimu."  

This preserves the past tense and correct technical meaning.
```

```
        <source>This pane shows a detailed description of the transaction</source>
        <translation>Šis langas sandorio detalų aprašymą</translation>
    
YES
The translation is incomplete and ungrammatical. It literally says "This window transaction detailed description" without a verb. A correct translation would include a verb such as "shows" (rodo).

Correct translation:
Šis langas rodo sandorio detalų aprašymą
```

```
        <source>Confirming (%1 of %2 recommended confirmations)</source>
        <translation>Patvirtinima (%1 iš rekomenduojamų patvirtinimų %2)</translation>
    
YES  
The noun "Patvirtinima" is in the accusative case, but here it should be nominative ("Patvirtinimas") as it is the subject of the sentence. Also, the order of the phrase is more fluent as "Patvirtinama (%1 iš %2 rekomenduojamų patvirtinimų)" to properly convey "Confirming (%1 of %2 recommended confirmations)" in Lithuanian.  

Correct translation:  
Patvirtinama (%1 iš %2 rekomenduojamų patvirtinimų)
```

```
        <source>Confirmed (%1 confirmations)</source>
        <translation>Patvirtinta (%1 patvirtinimas)</translation>
    
YES  
The translation is incorrect in the use of the plural form and case of the word "patvirtinimas". In Lithuanian, the word for "confirmations" (plural) should match the number and be in the genitive plural form. Since the source is "%1 confirmations" (plural), it should be "patvirtinimai" in the nominative plural or "patvirtinimų" in the genitive plural depending on context. Here, using the genitive plural after a number is correct, so it should be "patvirtinimų".

Correct translation:  
Patvirtinta (%1 patvirtinimų)
```

```
        <source>Enter address, transaction id, or label to search</source>
        <translation>Įveskite adresą ar žymę į paiešką</translation>
    
YES  
The translation is in Lithuanian, but the source text includes "transaction id" which is missing in the translation. Also, the translation uses only "adresą" (address) and "žymę" (label), missing "transaction id" (sandorio ID or transakcijos ID). This omission changes the meaning and makes the translation incomplete.

Correct translation:  
Įveskite adresą, sandorio ID arba žymę paieškai
```

```
        <source>Error loading %s: Wallet requires newer version of %s</source>
        <translation>Klaida įkeliant %s: Piniginei reikia naujesnės%s versijos</translation>
    
YES  
There is a missing space between "naujesnės" and "%s" in the translation, causing a formatting issue. Also, "Klaida" is Lithuanian for "error", but the provided translation is a mixture of Lithuanian and Latvian ("Piniginei" is Latvian). The Lithuanian word for "wallet" is "Piniginė" (with an ogonek on the "e"). The correct form would be:  

Correct translation:  
Klaida įkeliant %s: Piniginė reikalauja naujesnės %s versijos
```
</details>
