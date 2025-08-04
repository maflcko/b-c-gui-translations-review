# Translations Review by LLM (✨ experimental)

The review quality depends on the LLM and the language. Currently, a fast LLM without rate limits is used. If you are interested in better quality for a specific language, please file an issue to ask for it to be re-run with a stronger model.



<details><summary>lt</summary>

[If the result is of low quality, please file an issue to find a better LLM for this language.](../../issues/new?title=%5Blt%5D%20low%20quality)


```
        <source>There was an error trying to save the address list to %1. Please try again.</source>
        <extracomment>An error message. %1 is a stand-in argument for the name of the file we attempted to save to.</extracomment>
        <translation>Bandant išsaugoti adresų sąrašą - įvyko klaida keliant į %1. Prašome bandyti dar kartą.</translation>
    
YES, the translation contains erroneous content. The phrase "keliant į" means "lifting to" or "raising to", which does not make sense in this context. The correct translation should be "įrašant į" meaning "writing to".

NO
```

```
        <source>Enter the old passphrase and new passphrase for the wallet.</source>
        <translation>Įveskite seną ir naują slaptažodį.</translation>
    
YES
The translation is missing the word "passphrase" for the second instance, which makes it unclear that both are passphrases. Also, the word "slaptažodį" is a more general term for password. Considering the context of a wallet, it's more appropriate to use a word that implies a secret phrase.

Correct translation: Įveskite seną ir naują slaptafraze piniginei.
```

```
        <source>Remember that encrypting your wallet cannot fully protect your bitcoins from being stolen by malware infecting your computer.</source>
        <translation>Atminkite kad piniginės užšifravimas neužtrikrina kad jūsų bitkoinai negali būti pavogti dėl kenkėjiškų programų užkrėtusių jūsų kompiuterį.</translation>
    
YES, there is a spelling error in the translation. The word "neužtrikrina" should be "neužtikrina".

NO
```

```
        <source>Load Partially Signed Bitcoin Transaction from clipboard</source>
        <translation>Užkraukite dalinai pasirašytas Bitcoin transakcijas iš iškarpinės...</translation>
    
YES: The source text is singular ("Transaction"), but the translation uses a plural form ("transakcijas"). Additionally, the translation ends with an ellipsis (...), which is not present in the source text and implies continuation or incompleteness not intended by the original phrase.

Correct translation: Užkraukite dalinai pasirašytą Bitcoin transakciją iš iškarpinės.
```

```
        <source>Type: %1
</source>
        <translation>Spausti: %1
</translation>
    
YES, The word "Spausti" means "Press" in Lithuanian, not "Type". The correct translation for "Type" in this context is "Tipas".
Tipas: %1
```

```
        <source>Label: %1
</source>
        <translation>Antraštė: %1
</translation>
    
YES, The translation is not accurate. "Antraštė" means "heading" or "title", while "Label" in the context of Bitcoin typically refers to a descriptive tag or identifier. A more appropriate translation for "Label" in this context would be "Etiketė" or "Žyma".
Antraštė: %1
```

```
        <source>Copy change</source>
        <translation>Kopijuoti keisti</translation>
    
YES, the translation is inaccurate. "Keisti" in Lithuanian translates to "change" in the sense of modification or alteration, not the "change" amount in a financial transaction, which is more accurately translated as "grąža".

NO
```

```
        <source>change from %1 (%2)</source>
        <translation>pakeisti nuo %1 (%2)</translation>
    
YES, The word "pakeisti" means "to change" as a verb, but in the context of Bitcoin, "change" refers to the noun form, which is "grąža" in Lithuanian.
The correct translation is: grąža nuo %1 (%2)
```

```
        <source>Disable Private Keys</source>
        <translation>Atjungti Privačius Raktus</translation>
    
YES, the translation is problematic. While "Atjungti" can mean "disconnect" or "disable," in the context of private keys for Bitcoin, it's not the most appropriate term. It suggests a temporary action rather than a permanent removal or disabling. A more accurate translation would be "Pašalinti Privačius Raktus" (Remove Private Keys) or "Išjungti Privačius Raktus" (Turn Off Private Keys), but "Pašalinti" is generally preferred for security reasons when dealing with private keys.

"Pašalinti Privačius Raktus"
```

```
        <source>Number of script verification threads</source>
        <translation>Patvirtinimų skaičius</translation>
    
YES, The translation is inaccurate and lacks context. The Lithuanian word "Patvirtinimų" translates to "confirmations," which is related to Bitcoin but doesn't accurately convey "script verification threads." A more appropriate translation considering the context of Bitcoin would be "Skriptų tikrinimo gijų skaičius."

NO
```

```
        <source>Prune block storage to</source>
        <translation>blokuokite saugyklą į</translation>
    
YES, the translation is inaccurate and does not convey the intended meaning. The source text "Prune block storage to" is a command or instruction related to Bitcoin block storage management. The provided Lithuanian translation "blokuokite saugyklą į" translates to "block the storage to", which is semantically incorrect and nonsensical in this context. The term "prune" in computing refers to removing unnecessary data.

A more accurate translation would be:

<source>Prune block storage to</source>
<translation>Sumažinkite blokuojamos saugyklos dydį iki</translation>
```

```
        <source>Port of the proxy (e.g. 9050)</source>
        <translation>Tarpinio serverio preivadas (pvz, 9050)</translation>
    
YES, The Lithuanian word "preivadas" is not a real word in the Lithuanian language. The correct translation for "port" in this context is "prievadas".

NO
```

```
        <source>Minimize to the tray instead of the taskbar</source>
        <translation>M sumažinti langą bet ne užduočių juostą</translation>
    
YES, the translation is problematic because it does not accurately convey the meaning of the source text. The phrase "M sumažinti langą bet ne užduočių juostą" translates to "M to minimize the window but not the taskbar". This is not a grammatically correct or meaningful sentence in Lithuanian. The intended meaning is to minimize the application to the system tray, not the taskbar.

The correct translation should be: "Minimalizuoti į dėklą, o ne užduočių juostą".

NO
```

```
        <source>Choose the default subdivision unit to show in the interface and when sending coins.</source>
        <translation>Rodomų ir siunčiamų monetų kiekio matavimo vienetai</translation>
    
YES: The translation is too literal and doesn't capture the meaning of the original English sentence. It omits the crucial element of "default subdivision unit". The literal translation of "Choose the default subdivision unit to show in the interface and when sending coins" would be something like "Pasirinkite numatytąjį padalijimo vienetą, kurį rodyti sąsajoje ir siunčiant monetas."

Correct translation: Pasirinkite numatytąjį padalijimo vienetą, kurį rodyti sąsajoje ir siunčiant monetas.
```

```
        <source>Your current balance in watch-only addresses</source>
        <translation>Jūsų dabartinis balansas tik stebimų adresų</translation>
    
YES, The Lithuanian translation is grammatically incorrect and unnatural. The word order is awkward, and the possessive form of "addresses" is missing.

Correct translation: Jūsų dabartinis balansas tikriems stebimiems adresams
```

```
        <source>Cannot start bitcoin: click-to-pay handler</source>
        <translation>Negalima paleisti bitcoin: paspauskite sumokėti tvarkytojui</translation>
    
YES, The Lithuanian translation has a grammatical error. The phrase "paspauskite sumokėti tvarkytojui" is an imperative form that does not fit the context of an error message. The word "handler" is also not translated appropriately in this context. A more natural translation would be "Negalima paleisti bitcoin: spustelėkite, kad apmokėtumėte tvarkytuvės".

Here's a breakdown of the correction:
- "click-to-pay handler" is translated to "paspauskite sumokėti tvarkytojui". This is a literal translation that sounds awkward and grammatically incorrect in Lithuanian.
- A better translation would be "spustelėkite, kad apmokėtumėte tvarkytuvės" which means "click to pay the handler".
- The word "handler" in this context likely refers to a program or process that manages click-to-pay functionality.

NO
```

```
        <source>'bitcoin://' is not a valid URI. Use 'bitcoin:' instead.</source>
        <translation>„bitcoin: //“ nėra galiojantis URI. Vietoj to naudokite „bitcoin:“.</translation>
    
YES, The translation has a spacing error around the "//". The correct translation should be "„bitcoin://“ nėra galiojantis URI. Vietoj to naudokite „bitcoin:“."
```

```
        <source>Unban</source>
        <translation>Atblokuoti</translation>
    
YES, the translation of "Unban" to "Atblokuoti" is incorrect. "Atblokuoti" translates to "unblock" or "unban" in Lithuanian. However, in the context of Bitcoin, "unban" is not a standard term. If the intention is to refer to unblocking a Bitcoin address, "Atblokuoti adresą" would be more appropriate. If the intention is to simply unban something, "Atblokuoti" is a direct translation but lacks specific context. Considering the Bitcoin context provided, a more fitting translation would depend on the specific action meant by "unban." Without further context, "Atblokuoti" is the closest literal translation, but it's important to note its ambiguity in this specific domain.

Considering the possibility that "unban" in this context might refer to removing an address from a ban list, a more precise translation could be related to "remove from ban list." However, a direct translation of "unban" as "atblokuoti" is not completely wrong if the term "ban" has been used to mean "block."

Given the ambiguity and the fact that "unban" isn't a standard term in Bitcoin, a direct translation that is close but might not perfectly capture the nuance is "Atblokuoti".

Let's reconsider the common usage in related fields:

If "ban" means to "block access" or "blacklist," then "unban" means to "unblock access" or "remove from blacklist."

The Lithuanian word "atblokuoti" translates to "unblock." This seems like a reasonable translation if "ban" means to "block."

Let's assume "unban" means to remove a block.

NO
```

```
        <source>Custom change address</source>
        <translation>Pakeisti adresą</translation>
    
YES, the translation is inaccurate and potentially misleading. The original English "Custom change address" implies an address designated for receiving change in a Bitcoin transaction, and that this address is user-specified or customized. The Lithuanian translation "Pakeisti adresą" literally means "Change address" or "To change the address", which loses the nuance of it being a *custom* address for *change*. It sounds more like a command to change an address rather than a description of an address type.

A more accurate translation would be:

"Individualus grąžos adresas" or "Pasirinktinis grąžos adresas".

However, given the context of Bitcoin and the term "change" often referring to the change *amount* in a transaction, a slightly more descriptive and contextually appropriate translation could also be:

"Individualus adreso grąžai" (Individual address for change) or "Pasirinktinis adreso grąžai" (Custom address for change).

Considering the options, "Individualus grąžos adresas" is likely the most straightforward and understandable translation that captures the intended meaning.

NO
```

```
        <source>Using the fallbackfee can result in sending a transaction that will take several hours or days (or never) to confirm. Consider choosing your fee manually or wait until you have validated the complete chain.</source>
        <translation>Naudojant backbackfee gali būti siunčiamas sandoris, kuris užtruks kelias valandas ar dienas (arba niekada), kad patvirtintų. Apsvarstykite galimybę pasirinkti mokestį rankiniu būdu arba palaukite, kol patvirtinsite visą grandinę.</translation>
    
YES, The word "backbackfee" in the translation is a misspelling of "fallbackfee".
Naudojant fallbackfee gali būti siunčiamas sandoris, kuris užtruks kelias valandas ar dienas (arba niekada), kad patvirtintų. Apsvarstykite galimybę pasirinkti mokestį rankiniu būdu arba palaukite, kol patvirtinsite visą grandinę.
```

```
        <source>Add Recipient</source>
        <translation>A Pridėti gavėją</translation>
    
YES, The translation is problematic because it includes an unnecessary letter 'A' at the beginning of the translation. The correct translation is "Pridėti gavėją".
```

```
        <source>Enable Replace-By-Fee</source>
        <translation>Įgalinti keitimąsi mokesčiu</translation>
    
YES, the translation is problematic because it misinterprets "Replace-By-Fee" as "Enabling exchange by fee". The correct Lithuanian translation for "Replace-By-Fee" in the context of Bitcoin is "Pakeisti mokesčiu".

The correct translation should be:
Pakeisti mokesčiu
```

```
        <source>With Replace-By-Fee (BIP-125) you can increase a transaction's fee after it is sent. Without this, a higher fee may be recommended to compensate for increased transaction delay risk.</source>
        <translation>Naudojant Replace-by-Fend (BIP-125) galite išsiųsti sandorio mokestį vėliau. Be jo, gali būti rekomenduojamas didesnis mokestis, kad būtų kompensuota padidėjusi sandorio vėlavimo rizika.</translation>
    
YES: The translation incorrectly translates "fee" as "fend". The term should be "mokestis".

NO
```

```
        <source>Copy change</source>
        <translation>Kopijuoti keisti</translation>
    
YES, the translation is inaccurate. "Keisti" in Lithuanian translates to "change" in the sense of modification or alteration, not the "change" amount in a financial transaction, which is more accurately translated as "grąža".

NO
```

```
        <source>Duplicate address found: addresses should only be used once each.</source>
        <translation>Rastas dublikatas: adresai turėtų būti naudojami tik vieną kartą.</translation>
    
YES, the translation incorrectly omits the word "address" in the Lithuanian sentence. The correct translation should include the word "address" to accurately reflect the English source text.
Correct translation: Rastas dublikatas adresas: adresai turėtų būti naudojami tik vieną kartą.
```

```
        <source>Paste address from clipboard</source>
        <translation>Įvesti adresą iš mainų atminties</translation>
    
YES, The translation contains an error. The word "mainų" in Lithuanian means "exchange" or "swap", not "clipboard". The correct translation for "clipboard" is "mainų lentos" or "iškarpos".

Įvesti adresą iš mainų lentos
```

```
        <source>The Bitcoin address to sign the message with</source>
        <translation>Bitcoin adresas, kuriuo bus pasirašytas pranešimas su</translation>
    
YES, The translation is grammatically incorrect and does not accurately convey the meaning of the source text. The phrase "kuriuo bus pasirašytas pranešimas su" is awkward and doesn't make sense in this context.

A more accurate and natural translation would be: "Bitcoin adresas, kuriuo pasirašomas pranešimas".

Here's a breakdown of the issues:

*   **"su" at the end**: The word "su" (with) at the end of the translation is redundant and grammatically incorrect. It implies "with which the message will be signed with," which is a double preposition.
*   **"kuriuo bus pasirašytas"**: While grammatically correct in some contexts, "bus pasirašytas" (will be signed) is future tense. In this context, it's more natural to use a present tense or a more direct phrasing indicating the address *is used* for signing.

**Corrected Translation:** Bitcoin adresas, kuriuo pasirašomas pranešimas
```

```
        <source>Paste address from clipboard</source>
        <translation>Įvesti adresą iš mainų atminties</translation>
    
YES, The translation contains an error. The word "mainų" in Lithuanian means "exchange" or "swap", not "clipboard". The correct translation for "clipboard" is "mainų lentos" or "iškarpos".

Įvesti adresą iš mainų lentos
```

```
        <source>Sign the message to prove you own this Bitcoin address</source>
        <translation>Registruotis žinute įrodymuii, kad turite šį adresą</translation>
    
YES, The translation is inaccurate and does not convey the original meaning. The phrase "Sign the message" implies authorization or authentication, which is lost in the translation. The word "įrodymuii" has an extra 'i'.

NO, Sign the message to prove you own this Bitcoin address
```

```
        <source>Sign Message</source>
        <translation>Registruoti pranešimą</translation>
    
YES, The Lithuanian translation "Registruoti pranešimą" translates to "Register message" in English. The correct translation for "Sign Message" in the context of Bitcoin, which implies signing a message with a private key to prove ownership of an address, should be "Pasirašyti pranešimą".

Pasirašyti pranešimą
```

```
        <source>The signature did not match the message digest.</source>
        <translation>Parašas neatitinka žinutės.</translation>
    
YES, the translation is problematic. The word "digest" was omitted from the Lithuanian translation, which significantly alters the meaning of the original English sentence.

The correct translation should be: "Parašas neatitinka žinutės santraukos."
```

```
        <source>This pane shows a detailed description of the transaction</source>
        <translation>Šis langas sandorio detalų aprašymą</translation>
    
YES, The translation is missing the verb "shows". The correct translation is "Šis langas rodo sandorio detalia aprašymą".
```

```
        <source>Confirming (%1 of %2 recommended confirmations)</source>
        <translation>Patvirtinima (%1 iš rekomenduojamų patvirtinimų %2)</translation>
    
YES, the translation is problematic because the format specifiers are in the wrong order. The source text has "%1 of %2 recommended confirmations", meaning the first number should be the current confirmation count and the second number should be the total recommended confirmations. The translated text has "%1 iš rekomenduojamų patvirtinimų %2", which would be interpreted as "confirmation count out of recommended confirmations confirmation count", which is nonsensical.

Correct translation: Patvirtinama (%1 iš %2 rekomenduojamų patvirtinimų)
```

```
        <source>Confirmed (%1 confirmations)</source>
        <translation>Patvirtinta (%1 patvirtinimas)</translation>
    
YES, The translation is problematic because it uses the singular form of "patvirtinimas" (confirmation) when the source text uses the plural form "confirmations". This should be adjusted to match the plurality.
Patvirtinta (%1 patvirtinimai)
```

```
        <source>Enter address, transaction id, or label to search</source>
        <translation>Įveskite adresą ar žymę į paiešką</translation>
    
YES, The word "transaction id" was not translated.
Enter address, transaction id, or label to search
Įveskite adresą, operacijos ID ar žymę į paiešką
```

```
        <source>Error loading %s: Wallet requires newer version of %s</source>
        <translation>Klaida įkeliant %s: Piniginei reikia naujesnės%s versijos</translation>
    
YES, The translation is problematic because of missing space before the second format specifier %s.
Klaida įkeliant %s: Piniginei reikia naujesnės %s versijos
```
</details>
