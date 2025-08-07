# Translations Review by LLM (✨ experimental)

The review quality depends on the LLM and the language. Currently, a fast LLM without rate limits is used. If you are interested in better quality for a specific language, please file an issue to ask for it to be re-run with a stronger model.



<details><summary>el</summary>

[If the result is of low quality, please file an issue to find a better LLM for this language.](../../issues/new?title=%5Bel%5D%20low%20quality)


```
        <source>Warning: The Caps Lock key is on!</source>
        <translation>Προσοχη: το πλήκτρο Caps Lock είναι ενεργο.</translation>
    
YES
There are spelling and capitalization errors in the Greek translation. "Προσοχη" should be "Προσοχή" (with accent). "το" should be capitalized for consistency, and "ενεργο" should be "ενεργό" (with accent).

Correct translation:
Προσοχή: Το πλήκτρο Caps Lock είναι ενεργό!
```

```
        <source>Runaway exception</source>
        <translation>Αδυναμία αποθήκευσης παλιών δεδομένων πορτοφολιού</translation>
    
YES
The translation is incorrect. The Greek translation means "Unable to save old wallet data," which does not correspond to "Runaway exception." There is also no unwanted content or spam, but the meaning is wrong.

Correct translation:
Μη αναμενόμενη εξαίρεση
```

```
        <source>Minimize</source>
        <translation>Σμίκρυνε </translation>
    
YES
There is an unwanted trailing space at the end of the Greek translation. Also, "Σμίκρυνε" is a valid translation, but "Ελαχιστοποίηση" or "Ελαχιστοποίησε" is more commonly used in software UI for "Minimize".

Correct translation:
Ελαχιστοποίηση
```

```
        <source>Proxy is &lt;b&gt;enabled&lt;/b&gt;: %1</source>
        <translation>Proxy είναι&lt;b&gt;ενεργοποιημένος&lt;/b&gt;:%1 </translation>
    
YES
There are formatting issues with spacing: there should be spaces after "είναι" and after the colon. Additionally, in Greek, the grammatical gender agrees better as "ενεργοποιημένο" (neutral) to match "Proxy", which is neutral as a loanword.

Correct translation:
Proxy είναι &lt;b&gt;ενεργοποιημένο&lt;/b&gt;: %1
```

```
        <source>Connecting to peers…</source>
        <translation>Σύνδεση στους χρήστες...</translation>
    
YES
The translation of "peers" as "χρήστες" is inaccurate. In the context of Bitcoin, "peers" refers to other nodes in the network, not "users". The correct Greek term is "κόμβους" (nodes/peers).

Correct translation:
Σύνδεση στους κόμβους…
```

```
        <source>Request payments (generates QR codes and bitcoin: URIs)</source>
        <translation>Αίτηση πληρωμών (δημιουργεί QR codes και διευθύνσεις bitcoin: )</translation>
    
YES
The translation for "bitcoin: URIs" as "διευθύνσεις bitcoin:" is inaccurate. "URIs" should be "URI bitcoin:" (ενικός) or "bitcoin URI" in Greek, not "διευθύνσεις bitcoin:" (which means "bitcoin addresses:"), because not all URIs are addresses.

Correct translation:
Αίτηση πληρωμών (δημιουργεί QR codes και bitcoin: URI)
```

```
        <source>Load Partially Signed Bitcoin Transaction</source>
        <translation>Φόρτωση συναλλαγής Partially Signed Bitcoin</translation>
    
YES
The phrase "Partially Signed Bitcoin Transaction" should be translated into Greek rather than left in English. The translation should preferably use Greek for "Μερικώς Υπογεγραμμένη Συναλλαγή Bitcoin".

Correct translation:
Φόρτωση μερικώς υπογεγραμμένης συναλλαγής Bitcoin
```

```
        <source>Node window</source>
        <translation>Κόμβος παράθυρο</translation>
    
YES
The word order in Greek is incorrect. The correct order should be "Παράθυρο κόμβου", meaning "Node window".

Correct translation:
Παράθυρο κόμβου
```

```
        <source>Sending addresses</source>
        <translation>Αποστολή διεύθυνσης</translation>
    
YES
The translation is incorrect. The source "Sending addresses" is plural, meaning multiple addresses used for sending. The translation "Αποστολή διεύθυνσης" is singular ("Sending address"), which is inaccurate.

Correct translation:
Διευθύνσεις αποστολής
```

```
        <source>Hide</source>
        <translation>$Απόκρυψη</translation>
    
YES
The translation is incorrect because it includes an erroneous dollar sign ($) before the word. The correct translation should be:

Απόκρυψη
```

```
        <source>After Fee:</source>
        <translation>Ταρίφα αλλαγής:</translation>
    
YES
The translation is incorrect. "Ταρίφα αλλαγής" means "change fee" or "fee of change," and does not correctly translate "After Fee:". The correct Greek translation should directly refer to the amount after the fee is deducted.

Correct translation:
Μετά την προμήθεια:
```

```
        <source>Received with address</source>
        <translation>Παραλείφθηκε με την εξής διεύθυνση</translation>
    
YES
The Greek translation "Παραλείφθηκε με την εξής διεύθυνση" is incorrect. "Παραλείφθηκε" means "was omitted" or "skipped," which changes the meaning entirely. The correct translation should convey that something was received at a particular address.

Correct translation:
Ελήφθη στη διεύθυνση
```

```
        <source>Copy label</source>
        <translation>Αντιγραφή ετικέτα</translation>
    
YES
The Greek translation should use the accusative case for "label" after "copy", making it "ετικέτα" -> "ετικέτα" (accusative and nominative are the same for this feminine noun in Greek), but for clarity and fluency, the correct translation is "Αντιγραφή ετικέτας".

Correct translation:
Αντιγραφή ετικέτας
```

```
        <source>Copy transaction ID and output index</source>
        <translation>Αντιγραφή συναλλαγής ID και αποτελέσματος δείκτη</translation>
    
YES
The translation is problematic. The phrase "συναλλαγής ID" is not the correct way to express "transaction ID" in Greek; it should be "ταυτότητας συναλλαγής" or the commonly used English "transaction ID" transliterated as "ID συναλλαγής". Additionally, "αποτελέσματος δείκτη" is a mistranslation of "output index"; the correct term would be "δείκτη εξόδου".

Correct translation:
Αντιγραφή του ID συναλλαγής και του δείκτη εξόδου
```

```
        <source>Lock unspent</source>
        <translation>Lock διαθέσιμο</translation>
    
YES
The translation is partially incorrect. The English term "Lock unspent" should be translated to mean "To lock unspent outputs" (where "unspent" refers to unspent transaction outputs), but "Lock διαθέσιμο" literally means "Lock available", which may confuse Greek users.

Correct translation:
Κλείδωμα μη ξοδεμένων
or, more explicitly,
Κλείδωσε μη ξοδευμένα outputs

Either of these is suitable, with the first being more standard in Bitcoin wallet GUIs.
```

```
        <source>Can't list signers</source>
        <translation>Αδυναμία απαρίθμησης εγγεγραμμένων </translation>
    
YES
The translation is incomplete and slightly inaccurate. The word "signers" (υπογράφοντες/υπογράφοντες χρήστες) is missing, and the translation cuts off after "εγγεγραμμένων" (registered), which is not accurate for signers.

Correct translation:
Δεν είναι δυνατή η απαρίθμηση των υπογραφόντων
```

```
        <source>Are you sure you wish to migrate the wallet &lt;i&gt;%1&lt;/i&gt;?</source>
        <translation>Είστε σίγουρος/η ότι θέλετε να μετεγκαταστήσετε το πορτοφόλι σας; &lt;i&gt;%1&lt;/i&gt;;</translation>
    
YES
There are two issues:
1. The order of "%1" is incorrect (it should fall within the italics, like in the source, not at the end).
2. The sentence punctuation is off; the semicolon is used instead of a question mark.
3. The word "μετεγκαταστήσετε" is not as common as "μετακινήσετε" or "μεταφέρετε" for "migrate", but it's acceptable in a technical context.

Correct translation:
Είστε σίγουρος/η ότι θέλετε να μετεγκαταστήσετε το πορτοφόλι &lt;i&gt;%1&lt;/i&gt;;
```

```
        <source>Address "%1" already exists as a receiving address with label "%2" and so cannot be added as a sending address.</source>
        <translation>Η διεύθυνση "%1"  υπάρχει ήδη ως διεύθυνσης λήψης με ετικέτα "%2" και γιαυτό τον λόγο δεν μπορεί να προστεθεί ως διεύθυνση αποστολής.</translation>
    
YES
There are grammatical mistakes and a redundancy in the translation: "διεύθυνσης λήψης" should be "διεύθυνση λήψης" (nominative singular), and there's an unnecessary space after "%1". Also, "γιαυτό" should be spelled "γι' αυτό".

Correct translation:
Η διεύθυνση "%1" υπάρχει ήδη ως διεύθυνση λήψης με ετικέτα "%2" και γι' αυτό δεν μπορεί να προστεθεί ως διεύθυνση αποστολής.
```

```
        <source>Paste address from clipboard</source>
        <extracomment>Tooltip text for button that allows you to paste an address that is in your clipboard.</extracomment>
        <translation>Επικόλληση διεύθυνσης από το βιβλίο διευθύνσεων</translation>
    
YES
The translation incorrectly translates "clipboard" as "βιβλίο διευθύνσεων" ("address book"), which is not accurate. The correct translation for "clipboard" is "πρόχειρο".

Correct translation:
Επικόλληση διεύθυνσης από το πρόχειρο
```

```
        <source>Enabling pruning significantly reduces the disk space required to store transactions. All blocks are still fully validated. Reverting this setting requires re-downloading the entire blockchain.</source>
        <translation>Η ενεργοποίηση του κλαδέματος μειώνει τον απαιτούμενο χώρο για την αποθήκευση συναλλαγών. Όλα τα μπλόκ είναι πλήρως επαληθευμένα. Η επαναφορά αυτής της ρύθμισης απαιτεί επανεγκατάσταση ολόκληρου του blockchain.</translation>
    
YES
The translation is mostly accurate, but there is a significant issue with the translation of "re-downloading the entire blockchain" as "επανεγκατάσταση ολόκληρου του blockchain," which literally means "reinstallation of the entire blockchain." The original text refers to downloading the blockchain again, not reinstalling it. The word "επανεγκατάσταση" is not appropriate; "επανα-λήψη" (re-downloading) or "εκ νέου λήψη" would be better.

Correct translation:
Η ενεργοποίηση του κλαδέματος μειώνει σημαντικά τον απαιτούμενο χώρο στο δίσκο για την αποθήκευση συναλλαγών. Όλα τα μπλοκ εξακολουθούν να επαληθεύονται πλήρως. Η επαναφορά αυτής της ρύθμισης απαιτεί την εκ νέου λήψη ολόκληρου του blockchain.
```

```
        <source>Number of script verification threads</source>
        <translation>Αριθμός script και γραμμές επαλήθευσης</translation>
    
YES
The Greek translation is inaccurate. The English source is "Number of script verification threads", which refers to the number of threads used for script verification (a technical term in Bitcoin). The translation "Αριθμός script και γραμμές επαλήθευσης" means "Number of scripts and verification lines", which is incorrect and misleading.

Correct translation:
Αριθμός νημάτων επαλήθευσης σεναρίων
```

```
        <source>Prune block storage to</source>
        <translation>Αποκοπή αποκλεισμός αποθήκευσης στο</translation>
    
YES
The translation is inaccurate. The phrase "Αποκοπή αποκλεισμός αποθήκευσης στο" does not make sense in Greek; it incorrectly translates "prune" and misplaces the words. The correct translation should be:

Correct translation:
Περικοπή αποθήκευσης των μπλοκ σε
```

```
        <source>Whether to set subtract fee from amount as default or not.</source>
        <extracomment>Tooltip text for Options window setting that sets subtracting the fee from a sending amount as default.</extracomment>
        <translation>Να τεθεί ο φόρος αφαίρεσης από το ποσό στην προκαθορισμένη τιμή ή οχι. </translation>
    
YES
The translation uses "φόρος" (tax), which is incorrect. The term should be "προμήθεια" or "τέλος" for "fee" in this Bitcoin context. There is also a small spacing issue at the end ("οχι. " instead of "όχι.").

Correct translation:
Εάν θα οριστεί η αφαίρεση της προμήθειας από το ποσό ως προεπιλογή ή όχι.
```

```
        <source>Subtract fee from amount by default</source>
        <extracomment>An Options window setting to set subtracting the fee from a sending amount as default.</extracomment>
        <translation>Αφαιρέστε τέλος από το ποσό προεπιλογής</translation>
    
YES
The translation is somewhat inaccurate. The phrase "Αφαιρέστε τέλος από το ποσό προεπιλογής" translates back to "Subtract fee from the default amount", which changes the meaning. The original means "Subtract fee from the amount (being sent) by default", i.e., the application will by default subtract the transaction fee from the amount the user enters.

Correct translation:
Αφαίρεση της προμήθειας από το ποσό κατά προεπιλογή
```

```
        <source>Choose the default subdivision unit to show in the interface and when sending coins.</source>
        <translation>Διαλέξτε την προεπιλεγμένη υποδιαίρεση που θα εμφανίζεται όταν στέλνετε νομίσματα.</translation>
    
YES
The translation omits the part about showing the subdivision unit "in the interface". This changes the meaning and misses part of the source content.

Correct translation:
Επιλέξτε την προεπιλεγμένη μονάδα υποδιαίρεσης που θα εμφανίζεται στη διεπαφή και όταν στέλνετε νομίσματα.
```

```
        <source>Third-party URLs (e.g. a block explorer) that appear in the transactions tab as context menu items. %s in the URL is replaced by transaction hash. Multiple URLs are separated by vertical bar |.</source>
        <translation>Διευθύνσεις URL τρίτων (π.χ. μπλοκ explorer) που εμφανίζονται στην καρτέλα συναλλαγών ως συμφραζόμενα στοιχεία μενού. %sστο URL αντικαθίσταται από κατακερματισμό συναλλαγής. Πολλαπλές διευθύνσεις URL διαχωρίζονται με κάθετη γραμμή |.</translation>
    
YES
There is a small formatting issue: there is no space between "%s" and "στο" in the phrase "%sστο URL αντικαθίσταται από κατακερματισμό συναλλαγής." It should be "%s στο URL...", matching the spacing in the original.

Correct translation:
Διευθύνσεις URL τρίτων (π.χ. block explorer) που εμφανίζονται στην καρτέλα συναλλαγών ως στοιχεία του μενού περιβάλλοντος. Το %s στο URL αντικαθίσταται από το hash της συναλλαγής. Πολλαπλές διευθύνσεις URL διαχωρίζονται με κάθετη γραμμή |.
```

```
        <source>Configuration options</source>
        <extracomment>Window title text of pop-up box that allows opening up of configuration file.</extracomment>
        <translation> 
Επιλογές διαμόρφωσης</translation>
    
YES
There is a leading whitespace character (non-breaking space) at the start of the translation. This is a formatting issue and should be removed.

Correct translation:
Επιλογές διαμόρφωσης
```

```
        <source>Failed to sign transaction: %1</source>
        <translation>Αποτυχία εκπλήρωσης συναλλαγής: %1</translation>
    
YES
The translation is incorrect. The phrase "Αποτυχία εκπλήρωσης συναλλαγής" translates to "Failure to fulfill transaction", which is not the same as "Failed to sign transaction". The term "sign" should be translated as "υπογράψω" (to sign).

Correct translation:
Αποτυχία υπογραφής συναλλαγής: %1
```

```
        <source>Signed %1 inputs, but more signatures are still required.</source>
        <translation>Υπεγράφη %1 καταχώρηση, αλλά περισσότερες υπογραφές χρειάζονται.</translation>
    
YES
The Greek word "καταχώρηση" means "entry" or "record," but the context refers to transaction "inputs" in Bitcoin, which should be "είσοδοι" or "εισαγωγές." Also, the format specifier %1 should align in number (singular/plural), though this generic source uses "%1 inputs" (plural), so plural should be chosen in Greek as well.

Correct translation:
Υπεγράφησαν %1 είσοδοι, αλλά απαιτούνται ακόμα περισσότερες υπογραφές.
```

```
        <source>Node window</source>
        <translation>Κόμβος παράθυρο</translation>
    
YES
The word order in Greek is incorrect. The correct order should be "Παράθυρο κόμβου", meaning "Node window".

Correct translation:
Παράθυρο κόμβου
```

```
        <source>Min Ping</source>
        <translation>Ελάχιστο Min</translation>
    
YES
The translation is partially redundant and inaccurate. "Min" is already short for "Minimum" in English. "Ελάχιστο" is the correct Greek translation for "Minimum" or "Min." However, using both "Ελάχιστο" and "Min" together is unnecessary.

Correct translation:
Ελάχιστο Ping
```

```
        <source>Outbound Manual: added using RPC %1 or %2/%3 configuration options</source>
        <extracomment>Explanatory text for an outbound peer connection that was established manually through one of several methods. The numbered arguments are stand-ins for the methods available to establish manual connections.</extracomment>
        <translation>Εγχειρίδιο Εξερχόμενων: προστέθηκε χρησιμοποιώντας RPC %1ή %2/%3επιλογές διαμόρφωσης</translation>
    
YES
There are issues with missing spaces between words and slightly awkward phrasing. Specifically, "%1ή" should be "%1 ή" and "%3επιλογές" should be "%3 επιλογές". Also, "Εγχειρίδιο Εξερχόμενων" is a literal translation of "Outbound Manual" but, in this context, it should refer to a "manually established outbound connection", not a manual/book. Therefore, a clearer translation would be:

Correct translation:
Η εξερχόμενη σύνδεση προστέθηκε χειροκίνητα μέσω των επιλογών RPC %1 ή %2/%3 διαμόρφωσης
```

```
        <source>Outbound Feeler: short-lived, for testing addresses</source>
        <extracomment>Explanatory text for a short-lived outbound peer connection that is used to test the aliveness of known addresses.</extracomment>
        <translation>Εξερχόμενων Ελλείψεων: βραχύβια, για δοκιμή διευθύνσεων</translation>
    
YES
The translation is problematic. The English "Outbound Feeler" here refers to a short-lived outbound connection for testing addresses. The Greek "Εξερχόμενων Ελλείψεων" translates back to "Outbound Deficits" or "Outbound Shortcomings," which is incorrect. Also, the format is not consistent and the intended technical meaning is lost.

Correct translation:
Εξερχόμενη δοκιμαστική σύνδεση: βραχύβια, για τον έλεγχο διευθύνσεων
```

```
        <source>Ctrl+I</source>
        <translation>Ctrl+Ι </translation>
    
YES
The English letter "I" in "Ctrl+I" refers to the shortcut key, which should remain as "I" (Latin script) instead of being replaced by the Greek capital iota "Ι". The usage of the Greek "Ι" may cause the shortcut not to work as intended.

Correct translation:
Ctrl+I
```

```
        <source>Executing command using "%1" wallet</source>
        <translation> 
Εκτελέστε εντολή χρησιμοποιώντας το πορτοφόλι "%1"</translation>
    
YES
There is an unwanted leading whitespace before the translation and the use of the imperative "Εκτελέστε" ("Execute") rather than the present participle "Εκτελώντας" ("Executing") does not match the tone of the source. The correct translation should be:

Εκτελώντας εντολή χρησιμοποιώντας το πορτοφόλι "%1"
```

```
        <source>Welcome to the %1 RPC console.
Use up and down arrows to navigate history, and %2 to clear screen.
Use %3 and %4 to increase or decrease the font size.
Type %5 for an overview of available commands.
For more information on using this console, type %6.

%7WARNING: Scammers have been active, telling users to type commands here, stealing their wallet contents. Do not use this console without fully understanding the ramifications of a command.%8</source>
        <extracomment>RPC console welcome message. Placeholders %7 and %8 are style tags for the warning content, and they are not space separated from the rest of the text intentionally.</extracomment>
        <translation>Καλώς ήρθατε στην%1κονσόλα RPC.
Χρησιμοποιήστε τα πάνω και τα κάτω βέλη για πλοήγηση στο ιστορικό και%2εκκαθάριση της οθόνης.
Χρησιμοποιήστε%3και%4για να αυξήσετε ή να μειώσετε το μέγεθος της γραμματοσειράς.
Πληκτρολογήστε%5για επισκόπηση των διαθέσιμων εντολών.
Για περισσότερες πληροφορίες σχετικά με τη χρήση αυτής της κονσόλας, πληκτρολογήστε%6.

%7ΠΡΟΕΙΔΟΠΟΙΗΣΗ: Οι σκάμερς είναι ενεργοί, λέγοντας στους χρήστες να πληκτρολογούν εντολές εδώ, κλέβοντας το περιεχόμενο του πορτοφολιού τους. Μην χρησιμοποιείτε αυτήν την κονσόλα χωρίς να κατανοήσετε πλήρως τις συνέπειες μιας εντολής.%8</translation>
    
YES
There are spacing issues between the text and the placeholders (%1, %2, etc.). In Greek, just like in English, there should be spaces around placeholders so that substituted values are readable and correctly separated from surrounding text. Additionally, in some places like "στην%1κονσόλα" and "%7ΠΡΟΕΙΔΟΠΟΙΗΣΗ:", there is no space, which reduces readability.

Correct translation:
Καλώς ήρθατε στην %1 κονσόλα RPC.
Χρησιμοποιήστε τα πάνω και τα κάτω βέλη για πλοήγηση στο ιστορικό, και το %2 για εκκαθάριση της οθόνης.
Χρησιμοποιήστε τα %3 και %4 για να αυξήσετε ή να μειώσετε το μέγεθος της γραμματοσειράς.
Πληκτρολογήστε %5 για επισκόπηση των διαθέσιμων εντολών.
Για περισσότερες πληροφορίες σχετικά με τη χρήση αυτής της κονσόλας, πληκτρολογήστε %6.

%7ΠΡΟΕΙΔΟΠΟΙΗΣΗ: Οι σκάμερς είναι ενεργοί, λέγοντας στους χρήστες να πληκτρολογούν εντολές εδώ, κλέβοντας το περιεχόμενο του πορτοφολιού τους. Μην χρησιμοποιείτε αυτήν την κονσόλα χωρίς να κατανοήσετε πλήρως τις συνέπειες μιας εντολής.%8
```

```
        <source>Copy label</source>
        <translation>Αντιγραφή ετικέτα</translation>
    
YES
The Greek translation should use the accusative case for "label" after "copy", making it "ετικέτα" -> "ετικέτα" (accusative and nominative are the same for this feminine noun in Greek), but for clarity and fluency, the correct translation is "Αντιγραφή ετικέτας".

Correct translation:
Αντιγραφή ετικέτας
```

```
        <source>After Fee:</source>
        <translation>Ταρίφα αλλαγής:</translation>
    
YES
The translation is incorrect. "Ταρίφα αλλαγής" means "change fee" or "fee of change," and does not correctly translate "After Fee:". The correct Greek translation should directly refer to the amount after the fee is deducted.

Correct translation:
Μετά την προμήθεια:
```

```
        <source>Warning: Fee estimation is currently not possible.</source>
        <translation> 
Προειδοποίηση: Προς το παρόν δεν είναι δυνατή η εκτίμηση των εξόδων..</translation>
    
YES
There is a stray leading whitespace/newline before the translation and a double period at the end ("εκτίμηση των εξόδων.."), which should be a single period. The wording is accurate.

Correct translation:
Προειδοποίηση: Προς το παρόν δεν είναι δυνατή η εκτίμηση των εξόδων.
```

```
        <source>Inputs…</source>
        <translation>Προσθήκες...</translation>
    
YES
The translation of "Inputs…" as "Προσθήκες..." is not accurate. "Προσθήκες" means "Additions", not "Inputs". The correct translation of "Inputs" in the Bitcoin context is "Είσοδοι".

Correct translation:
Είσοδοι...
```

```
        <source>Creates a Partially Signed Bitcoin Transaction (PSBT) for use with e.g. an offline %1 wallet, or a PSBT-compatible hardware wallet.</source>
        <translation>Δημιουργεί μια συναλλαγή Bitcoin με μερική υπογραφή (PSBT) για χρήση με π.χ. ένα πορτοφόλι%1 εκτός σύνδεσης ή ένα πορτοφόλι υλικού συμβατό με το PSBT.</translation>
    
YES
There is a spacing issue between "πορτοφόλι" and "%1" — there should be a space: "πορτοφόλι %1". Also, "π.χ." should be followed by a space. The rest of the translation is otherwise accurate.

Correct translation:
Δημιουργεί μια συναλλαγή Bitcoin με μερική υπογραφή (PSBT) για χρήση με π.χ. ένα πορτοφόλι %1 εκτός σύνδεσης ή ένα πορτοφόλι υλικού συμβατό με το PSBT.
```

```
        <source>Please, review your transaction. You can create and send this transaction or create a Partially Signed Bitcoin Transaction (PSBT), which you can save or copy and then sign with, e.g., an offline %1 wallet, or a PSBT-compatible hardware wallet.</source>
        <extracomment>Text to inform a user attempting to create a transaction of their current options. At this stage, a user can send their transaction or create a PSBT. This string is displayed when both private keys and PSBT controls are enabled.</extracomment>
        <translation>Παρακαλώ, ελέγξτε τη συναλλαγή σας. Μπορείτε να δημιουργήσετε και να στείλετε αυτήν τη συναλλαγή ή να δημιουργήσετε μια μερικώς υπογεγραμμένη συναλλαγή Bitcoin (PSBT), την οποία μπορείτε να αποθηκεύσετε ή να αντιγράψετε και στη συνέχεια να υπογράψετε, π.χ. με ένα πορτοφόλι εκτός σύνδεσης%1ή ένα πορτοφόλι υλικού συμβατό με PSBT.</translation>
    
YES
There are issues with spacing before "%1" and after it in the Greek translation; there should be a space before and after the placeholder "%1", per the source meaning ("offline %1 wallet"). The translation currently merges "%1" against the word "εκτός σύνδεσης" and "ή", which produces the incorrect "εκτός σύνδεσης%1ή".

Correct translation:
Παρακαλώ, ελέγξτε τη συναλλαγή σας. Μπορείτε να δημιουργήσετε και να στείλετε αυτήν τη συναλλαγή ή να δημιουργήσετε μια μερικώς υπογεγραμμένη συναλλαγή Bitcoin (PSBT), την οποία μπορείτε να αποθηκεύσετε ή να αντιγράψετε και στη συνέχεια να υπογράψετε, π.χ. με ένα πορτοφόλι εκτός σύνδεσης %1 ή ένα πορτοφόλι υλικού συμβατό με PSBT.
```

```
        <source>Not signalling Replace-By-Fee, BIP-125.</source>
        <translation> 
Δεν σηματοδοτεί την Aντικατάσταση-Aπό-Έξοδο, BIP-125.</translation>
    
YES
There are two issues:
1. Leading whitespace before the Greek sentence in the <translation> tag, which should be removed.
2. The translation for "Replace-By-Fee" is inaccurate. The correct translation should keep the term "Replace-By-Fee" (as it is a specific Bitcoin protocol term), possibly with a transliteration or an explanation in parentheses if needed, but should not translate it as "Aντικατάσταση-Aπό-Έξοδο" (which means 'Replace-From-Output', which is misleading and incorrect).

Correct translation:
Δεν σηματοδοτεί το Replace-By-Fee, BIP-125.
```

```
        <source>Paste address from clipboard</source>
        <translation>Επικόλληση διεύθυνσης από το βιβλίο διευθύνσεων</translation>
    
YES
The translation is inaccurate. The English source says "clipboard" (πρόχειρο), but the translation says "address book" (βιβλίο διευθύνσεων).

Correct translation:
Επικόλληση διεύθυνσης από το πρόχειρο
```

```
        <source>Signatures - Sign / Verify a Message</source>
        <translation>Υπογραφές - Είσοδος / Επαλήθευση Mηνύματος</translation>
    
YES
The term "Είσοδος" means "Login" or "Entrance", which is incorrect here. The correct translation for "Sign" in the cryptographic sense is "Υπογραφή". Also, the capitalization of "Mηνύματος" should be corrected to "Μηνύματος". The correct translation should be:

Υπογραφές - Υπογραφή / Επαλήθευση Μηνύματος
```

```
        <source>The Bitcoin address to sign the message with</source>
        <translation>Διεύθυνση Bitcoin που θα σταλεί το μήνυμα</translation>
    
YES
The translation is inaccurate. The English text refers to "the Bitcoin address to sign the message with", but the Greek translation means "Bitcoin address to which the message will be sent." This changes the intended meaning.

Correct translation:
Η διεύθυνση Bitcoin με την οποία θα υπογραφεί το μήνυμα
```

```
        <source>Paste address from clipboard</source>
        <translation>Επικόλληση διεύθυνσης από το βιβλίο διευθύνσεων</translation>
    
YES
The translation is inaccurate. The English source says "clipboard" (πρόχειρο), but the translation says "address book" (βιβλίο διευθύνσεων).

Correct translation:
Επικόλληση διεύθυνσης από το πρόχειρο
```

```
        <source>Enter the receiver's address, message (ensure you copy line breaks, spaces, tabs, etc. exactly) and signature below to verify the message. Be careful not to read more into the signature than what is in the signed message itself, to avoid being tricked by a man-in-the-middle attack. Note that this only proves the signing party receives with the address, it cannot prove sendership of any transaction!</source>
        <translation>Εισαγάγετε τη διεύθυνση του παραλήπτη, το μήνυμα (βεβαιωθείτε ότι αντιγράφετε σωστά τα διαλείμματα γραμμής, τα κενά, τις καρτέλες κλπ.) Και την υπογραφή παρακάτω για να επαληθεύσετε το μήνυμα. Προσέξτε να μην διαβάσετε περισσότερα στην υπογραφή από ό,τι είναι στο ίδιο το υπογεγραμμένο μήνυμα, για να αποφύγετε να εξαπατήσετε από μια επίθεση στον άνθρωπο στη μέση. Σημειώστε ότι αυτό αποδεικνύει μόνο ότι η υπογραφή συμβαλλόμενο μέρος λαμβάνει με τη διεύθυνση, δεν μπορεί να αποδειχθεί αποστολή οποιασδήποτε συναλλαγής!</translation>
    
YES
There are several issues in the Greek translation:
- The punctuation before "Και την υπογραφή" (capitalization after a period) is incorrect; "και" should not be capitalized and should not begin a new sentence here.
- The phrase "καρτέλες" should be "tab χαρακτήρες" or "tabulators" for clarity; "καρτέλες" means 'tabs' as in tabs of a browser or folder, not tab characters.
- "να εξαπατήσετε από μια επίθεση στον άνθρωπο στη μέση" is incorrect; it translates to "be deceived by an attack on the man in the middle" instead of "be deceived by a man-in-the-middle attack". The correct Greek term is "επίθεση τύπου man-in-the-middle" or "επίθεση με ενδιάμεσο".
- "η υπογραφή συμβαλλόμενο μέρος λαμβάνει με τη διεύθυνση" is not a grammatical phrase and does not make sense. It should more closely say "το συμβαλλόμενο μέρος λαμβάνει με τη διεύθυνση".
- "αποστολή οποιασδήποτε συναλλαγής" is missing a "την" or does not flow naturally.

Correct translation:
Εισαγάγετε τη διεύθυνση του παραλήπτη, το μήνυμα (βεβαιωθείτε ότι αντιγράφετε ακριβώς τα διαλείμματα γραμμής, τα κενά, τους χαρακτήρες tab κ.λπ.) και την υπογραφή παρακάτω για να επαληθεύσετε το μήνυμα. Προσέξτε να μην ερμηνεύσετε περισσότερα στην υπογραφή από ό,τι περιέχει το ίδιο το υπογεγραμμένο μήνυμα, ώστε να αποφύγετε να εξαπατηθείτε από μια επίθεση τύπου man-in-the-middle. Σημειώστε ότι αυτό αποδεικνύει μόνο ότι το υπογράφον μέρος μπορεί να λαμβάνει με τη διεύθυνση· δεν μπορεί να αποδείξει την αποστολή κάποιας συναλλαγής!
```

```
        <source>not accepted</source>
        <translation>μη έγκυρο</translation>
    
YES
The translation is inaccurate. "μη έγκυρο" means "invalid," not "not accepted." The correct Greek translation for "not accepted" is "δεν έγινε αποδεκτό".

Correct translation:
δεν έγινε αποδεκτό
```

```
        <source>Confirmed (%1 confirmations)</source>
        <translation>Επιβεβαίωση (%1 επιβεβαιώσεις)</translation>
    
YES
The translation is inaccurate. The English source "Confirmed" translates to "Επιβεβαιωμένο" or "Επιβεβαιωμένη" in Greek, meaning "Confirmed" (past participle/adjective), while "Επιβεβαίωση" means "Confirmation" (noun), which changes the meaning. Additionally, the format specifier %1 is correctly preserved. There are no whitespace or format issues.

Correct translation:
Επιβεβαιωμένο (%1 επιβεβαιώσεις)
```

```
        <source>Immature (%1 confirmations, will be available after %2)</source>
        <translation>Άτομο (%1 επιβεβαιώσεις, θα είναι διαθέσιμες μετά το %2)</translation>
    
YES
The word "Άτομο" means "Person" in Greek, which is incorrect in this context. The correct translation for "Immature" in the context of confirmations (e.g., mining rewards not yet spendable) should be "Ανεπιβεβαίωτο" or "Ανεπεξέργαστο" or "Ανώριμο", with "Ανώριμο" being the most direct.

Correct translation:
Ανώριμο (%1 επιβεβαιώσεις, θα είναι διαθέσιμο μετά από %2)
```

```
        <source>Whether or not a watch-only address is involved in this transaction.</source>
        <translation>Είτε πρόκειται για μια διεύθυνση μόνο για ρολόι, είτε όχι, σε αυτήν τη συναλλαγή.</translation>
    
YES
The translation is a bit literal and awkward in Greek ("διεύθυνση μόνο για ρολόι" is not an idiomatically correct way to say "watch-only address"). In the Bitcoin context, the term "watch-only address" is typically rendered as "διεύθυνση μόνο για παρακολούθηση" in Greek.

Correct translation:
Αν εμπλέκεται ή όχι μια διεύθυνση μόνο για παρακολούθηση σε αυτήν τη συναλλαγή.
```

```
        <source>Copy label</source>
        <translation>Αντιγραφή ετικέτα</translation>
    
YES
The Greek translation should use the accusative case for "label" after "copy", making it "ετικέτα" -> "ετικέτα" (accusative and nominative are the same for this feminine noun in Greek), but for clarity and fluency, the correct translation is "Αντιγραφή ετικέτας".

Correct translation:
Αντιγραφή ετικέτας
```

```
        <source>Copy full transaction details</source>
        <translation>Αντιγραφή όλων των πληροφοριών συναλλαγής λεπτομερειών</translation>
    
YES
The translation is grammatically awkward and incorrect. It translates literally to "Copy all of information transaction details," which is redundant and unclear in Greek. A more natural and accurate translation is:

Αντιγραφή πλήρων λεπτομερειών συναλλαγής

This preserves both meaning and clarity.
```

```
        <source>Increase transaction fee</source>
        <translation>Αύξηση κρατήσεων συναλλαγής</translation>
    
YES
The translation is problematic. The word "κρατήσεων" means "reservations" or "withholdings," which is incorrect in this context. The correct term for "fee" related to transactions is "προμήθεια" or "τέλος". The correct translation should be:

Αύξηση προμήθειας συναλλαγής
```

```
        <source>No wallet has been loaded.
Go to File &gt; Open Wallet to load a wallet.
- OR -</source>
        <translation>Δεν έχει φορτωθεί κανένα πορτοφόλι.
Μεταβείτε στο Αρχείο&gt;Άνοιγμα πορτοφολιού για φόρτωση.
-Η-</translation>
    
YES
There are some spacing issues:

1. In "Αρχείο&gt;Άνοιγμα", there should be a space before and after "&gt;", i.e., "Αρχείο &gt; Άνοιγμα".
2. "-Η-" should have spaces, as in the source "- OR -", so it should be "- Η -".

Correct translation:
Δεν έχει φορτωθεί κανένα πορτοφόλι.
Μεταβείτε στο Αρχείο &gt; Άνοιγμα πορτοφολιού για να φορτώσετε ένα πορτοφόλι.
- Η -

Additionally, "για φόρτωση" is less natural in Greek; "για να φορτώσετε ένα πορτοφόλι" matches the English tone better.
```

```
        <source>New fee:</source>
        <translation>Νέο έξοδο:</translation>
    
YES
The English term "fee" in the context of Bitcoin refers specifically to a transaction fee, not a general "expense" (which "έξοδο" means in Greek). The correct term is "χρέωση" or "τέλος".

Correct translation:
Νέο τέλος:
```

```
        <source>Could not commit transaction</source>
        <translation>Δεν ήταν δυνατή η ανάληψη συναλλαγής</translation>
    
YES
The Greek translation is inaccurate. "Ανάληψη συναλλαγής" means "withdrawal of transaction," which does not accurately convey "commit transaction." The correct phrase should indicate that the transaction could not be committed (i.e., finalized or saved).

Correct translation:
Δεν ήταν δυνατή η καταχώρηση της συναλλαγής
```

```
        <source>Prune configured below the minimum of %d MiB.  Please use a higher number.</source>
        <translation>Ο δακτύλιος έχει διαμορφωθεί κάτω από το ελάχιστο %d MiB. Χρησιμοποιήστε έναν υψηλότερο αριθμό.</translation>
    
YES
The translation is incorrect. The English term "Prune" in the Bitcoin context refers to "pruning" (reducing blockchain data), not "δακτύλιος" (which means "ring"). Also, the phrase "διαμορφωθεί" is correct for "configured," but the translation as a whole misrepresents the meaning.

Correct translation:
Η περικοπή έχει ρυθμιστεί κάτω από το ελάχιστο των %d MiB. Παρακαλώ χρησιμοποιήστε έναν μεγαλύτερο αριθμό.
```

```
        <source>Total length of network version string (%i) exceeds maximum length (%i). Reduce the number or size of uacomments.</source>
        <translation>Το συνολικό μήκος της συμβολοσειράς έκδοσης δικτύου (%i) υπερβαίνει το μέγιστο μήκος (%i). Μειώστε τον αριθμό ή το μέγεθος των προϊόντων.</translation>
    
YES
The word "προϊόντων" in Greek means "products", which is incorrect in this technical context. The English source refers to "uacomments" (user agent comments), not products. The word "uacomments" usually stays in English in highly technical contexts, or could be described as "σχόλια χρήστη πρακτορείου" if absolutely necessary, but should not be translated as "προϊόντων".

Correct translation:
Το συνολικό μήκος της συμβολοσειράς έκδοσης δικτύου (%i) υπερβαίνει το μέγιστο επιτρεπτό μήκος (%i). Μειώστε τον αριθμό ή το μέγεθος των uacomments.

Alternatively (keeping "uacomments" untranslated for clarity):
Το συνολικό μήκος της συμβολοσειράς έκδοσης δικτύου (%i) υπερβαίνει το μέγιστο μήκος (%i). Μειώστε τον αριθμό ή το μέγεθος των uacomments.
```

```
        <source>Incorrect or no genesis block found. Wrong datadir for network?</source>
        <translation>Ανακαλύφθηκε λάθος ή δεν βρέθηκε μπλοκ γενετικής. Λάθος δεδομένων για το δίκτυο;</translation>
    
YES
The translation has inaccuracies:
- "μπλοκ γενετικής" is an incorrect translation for "genesis block." The correct term is "μπλοκ γένεσης."
- "Λάθος δεδομένων για το δίκτυο;" does not precisely mirror "Wrong datadir for network?" A better translation would mention the "κατάλογο δεδομένων".

Correct translation:
Εντοπίστηκε λάθος ή δεν βρέθηκε μπλοκ γένεσης. Μήπως χρησιμοποιείτε λάθος κατάλογο δεδομένων για το δίκτυο;
```

```
        <source>Invalid -onion address or hostname: '%s'</source>
        <translation>Μη έγκυρη διεύθυνση μητρώου ή όνομα κεντρικού υπολογιστή: '%s'</translation>
    
YES
The translation "Μη έγκυρη διεύθυνση μητρώου ή όνομα κεντρικού υπολογιστή" incorrectly translates "-onion address" as "διεύθυνση μητρώου" which means "registry address," not an ".onion" address (which refers to a Tor network address). 

Correct translation:
Μη έγκυρη διεύθυνση -onion ή όνομα κεντρικού υπολογιστή: '%s'
```

```
        <source>Prune cannot be configured with a negative value.</source>
        <translation>Ο δακτύλιος δεν μπορεί να ρυθμιστεί με αρνητική τιμή.</translation>
    
YES
The translation uses "Ο δακτύλιος" which means "the ring" instead of the correct term for "prune" (which refers to "αραίωση" or "περιορισμός" in the context of Bitcoin). This is an erroneous translation.

Correct translation:
Η αραίωση δεν μπορεί να ρυθμιστεί με αρνητική τιμή.
```

```
        <source>Settings file could not be written</source>
        <translation>Το αρχείο ρυθμίσεων δεν μπόρεσε να επεξεργασθεί</translation>
    
YES
The translation is inaccurate. The source refers to the file not being writable (i.e., unable to be saved/written), but the translation says it could not be "edited".

Correct translation:
Το αρχείο ρυθμίσεων δεν μπόρεσε να γραφτεί
```
</details>

Number of issues: 64.
