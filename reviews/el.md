# Translations Review by LLM (✨ experimental)

The review quality depends on the LLM and the language. Currently, a fast LLM without rate limits is used. If you are interested in better quality for a specific language, please file an issue to ask for it to be re-run with a stronger model.



<details><summary>el</summary>

[If the result is of low quality, please file an issue to find a better LLM for this language.](../../issues/new?title=%5Bel%5D%20low%20quality)


```
        <source>Create a new address</source>
        <translation>Δημιουργία νέας διεύθυνσης </translation>
    
YES: The translation has an extra space before the closing tag.
Δημιουργία νέας διεύθυνσης
```

```
        <source>Wallet encryption failed due to an internal error. Your wallet was not encrypted.</source>
        <translation>Η κρυπτογράφηση του πορτοφολιού απέτυχε λογω εσωτερικού σφάλματος. Το πορτοφολι δεν κρυπτογραφηθηκε.</translation>
    
YES, The translation contains an ungrammatical contraction "λογω" which should be "λόγω". The translation is also missing a space before "εσωτερικού". Also, the word "πορτοφολι" should be "πορτοφόλι". The correct translation is: Η κρυπτογράφηση του πορτοφολιού απέτυχε λόγω εσωτερικού σφάλματος. Το πορτοφόλι δεν κρυπτογραφήθηκε.
```

```
        <source>Warning: The Caps Lock key is on!</source>
        <translation>Προσοχη: το πλήκτρο Caps Lock είναι ενεργο.</translation>
    
YES. The translation is missing the closing punctuation mark and has a grammatical error.

Correct translation: Προσοχή: το πλήκτρο Caps Lock είναι ενεργοποιημένο!
```

```
        <source>Runaway exception</source>
        <translation>Αδυναμία αποθήκευσης παλιών δεδομένων πορτοφολιού</translation>
    
YES: The translation is completely inaccurate and does not convey the meaning of the source text. The Greek text refers to an inability to save old wallet data, while the English text is a general term for an uncontrolled exception.

Correct translation: Ανεξέλεγκτη εξαίρεση
```

```
        <source>A fatal error occurred. Check that settings file is writable, or try running with -nosettings.</source>
        <extracomment>Explanatory text shown on startup when the settings file could not be written. Prompts user to check that we have the ability to write to the file. Explains that the user has the option of running without a settings file.</extracomment>
        <translation>Συνέβη ένα μοιραίο σφάλμα. Ελέγξτε ότι το αρχείο ρυθμίσεων είναι προσπελάσιμο, ή δοκιμάστε να τρέξετε με -nosettings.</translation>
    
YES: The translation mistranslates "writable" as "προσπελάσιμο" (accessible) instead of "εγγράψιμο" (writable).
Συνέβη ένα μοιραίο σφάλμα. Ελέγξτε ότι το αρχείο ρυθμίσεων είναι εγγράψιμο, ή δοκιμάστε να τρέξετε με -nosettings.
```

```
        <source>Onion</source>
        <comment>network name</comment>
        <extracomment>Name of Tor network in peer info</extracomment>
        <translation>Onion (κρυφές υπηρεσίες)</translation>
    
YES: The translation is problematic because it adds extra information not present in the source text. The source text simply translates "Onion" to "Onion" in Greek, but the translation adds "(κρυφές υπηρεσίες)" which means "(hidden services)". This is extraneous and alters the meaning of the original text.
Correct translation: Onion
```

```
        <source>Feeler</source>
        <extracomment>Short-lived peer connection type that tests the aliveness of known addresses.</extracomment>
        <translation>Feeler (εξερχόμενη σύνδεση βραχείας διάρκειας)</translation>
    
YES. The Greek translation is not a direct translation of "Feeler" and includes extraneous information. The term "Feeler" in this context refers to a specific type of connection in Bitcoin, and the translation should ideally reflect that. Additionally, the extraneous information about "εξερχόμενη σύνδεση βραχείας διάρκειας" is too long and might be considered problematic in some UI contexts.

Correct translation: Feeler
```

```
        <source>Minimize</source>
        <translation>Σμίκρυνε </translation>
    
YES. The translation has an extra space at the end of the word.
Σμίκρυνε
```

```
        <source>Proxy is &lt;b&gt;enabled&lt;/b&gt;: %1</source>
        <translation>Proxy είναι&lt;b&gt;ενεργοποιημένος&lt;/b&gt;:%1 </translation>
    
YES - The translation has a trailing space after "%1".
Proxy is &lt;b&gt;enabled&lt;/b&gt;: %1
```

```
        <source>Connecting to peers…</source>
        <translation>Σύνδεση στους χρήστες...</translation>
    
YES, The translation is problematic. The Greek word "χρήστες" means "users," which is not the correct translation for "peers" in the context of Bitcoin networking. In Bitcoin, "peers" refers to other nodes on the network.

The correct translation should be:
<translation>Σύνδεση στους ομότιμους...</translation>
```

```
        <source>Request payments (generates QR codes and bitcoin: URIs)</source>
        <translation>Αίτηση πληρωμών (δημιουργεί QR codes και διευθύνσεις bitcoin: )</translation>
    
YES: The translation incorrectly omits the placeholder for the Bitcoin URI. It should be: "Αίτηση πληρωμών (δημιουργεί QR codes και bitcoin: %s URIs)"
```

```
        <source>Load Partially Signed Bitcoin Transaction</source>
        <translation>Φόρτωση συναλλαγής Partially Signed Bitcoin</translation>
    
YES - The translation is not accurate. The term "Partially Signed Bitcoin Transaction" should be translated as "Μερικώς Υπογεγραμμένη Συναλλαγή Bitcoin".

Φόρτωση Μερικώς Υπογεγραμμένης Συναλλαγής Bitcoin
```

```
        <source>Load Partially Signed Bitcoin Transaction from clipboard</source>
        <translation>Φόρτωση συναλλαγής Partially Signed Bitcoin από το πρόχειρο</translation>
    
YES - The translation uses the English phrase "Partially Signed Bitcoin" instead of translating it into Greek.
Correct translation: Φόρτωση μερικώς υπογεγραμμένης συναλλαγής Bitcoin από το πρόχειρο
```

```
        <source>Node window</source>
        <translation>Κόμβος παράθυρο</translation>
    
YES
The Greek word for "window" is "παράθυρο" (parathiro). However, the word order is incorrect. The correct translation would be "Παράθυρο κόμβου".
Παράθυρο κόμβου
```

```
        <source>Sending addresses</source>
        <translation>Αποστολή διεύθυνσης</translation>
    
YES: The translation is not accurate. The English text is plural ("Sending addresses"), while the Greek translation is singular ("Αποστολή διεύθυνσης" which means "Sending address"). The correct translation should be plural as well.

Correct translation: Αποστολή διευθύνσεων
```

```
        <source>Hide</source>
        <translation>$Απόκρυψη</translation>
    
YES, the translation is problematic. The '$' symbol is not part of the Greek alphabet and is likely an error. It should be removed.

NO, $Απόκρυψη
```

```
        <source>Show Peers tab</source>
        <extracomment>A context menu item. The "Peers tab" is an element of the "Node window".</extracomment>
        <translation>Προβολή καρτέλας Χρηστών</translation>
    
YES - The translation is incorrect. The Greek word "Χρηστών" means "Users", but the English text means "Peers".
Correct translation: Προβολή καρτέλας Ομότιμων
```

```
        <source>Cannot create new wallet, the software was compiled without sqlite support (required for descriptor wallets)</source>
        <translation>Δεν είναι δυνατή η δημιουργία νέου πορτοφολιού, το λογισμικό μεταγλωττίστηκε χωρίς SQLite υποστήριξη (απαιτείται για κρυπτογραφημένα πορτοφόλια)</translation>
    
YES: The Greek translation uses "κρυπτογραφημένα πορτοφόλια" which translates to "encrypted wallets". However, the English source text says "descriptor wallets". Therefore, the translation is not accurate.

Correct translation: Δεν είναι δυνατή η δημιουργία νέου πορτοφολιού, το λογισμικό μεταγλωττίστηκε χωρίς SQLite υποστήριξη (απαιτείται για descriptor wallets)
```

```
        <source>After Fee:</source>
        <translation>Ταρίφα αλλαγής:</translation>
    
YES: The translation incorrectly translates "After Fee" to "Ταρίφα αλλαγής" (Change Fee) instead of a phrase indicating what remains after a fee is deducted.
Correct translation: Μετά την προμήθεια:
```

```
        <source>Received with address</source>
        <translation>Παραλείφθηκε με την εξής διεύθυνση</translation>
    
YES, The translation is incorrect. The Greek word "Παραλείφθηκε" means "was skipped" or "was omitted," which is the opposite of "Received."

Correct translation: Λήφθηκε με τη διεύθυνση
```

```
        <source>Copy label</source>
        <translation>Αντιγραφή ετικέτα</translation>
    
YES: The translation is grammatically incorrect in Greek. The correct translation should be "Αντιγραφή ετικέτας".
Αντιγραφή ετικέτας
```

```
        <source>Copy transaction ID and output index</source>
        <translation>Αντιγραφή συναλλαγής ID και αποτελέσματος δείκτη</translation>
    
YES: The translation incorrectly translates "output index" as "αποτελέσματος δείκτη" which means "result index". The correct translation for "output index" in the context of Bitcoin transactions is "δείκτη εξόδου".

Correct translation: Αντιγραφή συναλλαγής ID και δείκτη εξόδου
```

```
        <source>Lock unspent</source>
        <translation>Lock διαθέσιμο</translation>
    
YES
The Greek translation is inaccurate and does not convey the intended meaning of "Lock unspent" in the context of Bitcoin. "Διαθέσιμο" means "available" but doesn't capture the nuance of "unspent" in a Bitcoin transaction.

Correct translation: Κλείδωμα αχρησιμοποίητων
```

```
        <source>Can't list signers</source>
        <translation>Αδυναμία απαρίθμησης εγγεγραμμένων </translation>
    
YES: The translation "Αδυναμία απαρίθμησης εγγεγραμμένων" is a literal translation of "Cannot list registered" and misses the context of "signers". A more accurate translation would be "Αδυναμία απαρίθμησης των υπογραφόντων".
```

```
        <source>Are you sure you wish to migrate the wallet &lt;i&gt;%1&lt;/i&gt;?</source>
        <translation>Είστε σίγουρος/η ότι θέλετε να μετεγκαταστήσετε το πορτοφόλι σας; &lt;i&gt;%1&lt;/i&gt;;</translation>
    
YES - The Greek translation incorrectly includes the word "σας" (your) which is not present in the source text. Additionally, the semicolon at the end of the sentence is also not present in the source.

Correct translation: Είστε σίγουρος/η ότι θέλετε να μετεγκαταστήσετε το πορτοφόλι &lt;i&gt;%1&lt;/i&gt;;
```

```
        <source>Watchonly scripts have been migrated to a new wallet named '%1'.</source>
        <translation>Τα σενάρια παρακολούθησης μόνο μετεγκαταστάθηκαν σε νέο πορτοφόλι ονόματι '%1'.</translation>
    
YES - The translation is problematic because it uses a very literal and unnatural translation of "Watchonly". In the context of Bitcoin, "watchonly" refers to a wallet that can only monitor transactions but cannot spend funds. The current translation "σενάρια παρακολούθησης μόνο" means "monitoring only scripts", which is not the standard terminology.

A more appropriate translation would be to use a term that conveys the idea of being read-only or being able to view without spending.

Correct translation: Τα πορτοφόλια μόνο για παρακολούθηση μεταφέρθηκαν σε ένα νέο πορτοφόλι με όνομα '%1'.
```

```
        <source>Are you sure you wish to close all wallets?</source>
        <translation>Είσαι σίγουροι ότι επιθυμείτε το κλείσιμο όλων των πορτοφολιών;</translation>
    
YES: The translation uses the formal plural "Είσαι σίγουροι" which is grammatically incorrect. It should either be the formal singular "Είστε σίγουροι" or the informal singular "Είσαι σίγουρος". Given the context of software, the formal singular is more appropriate.

Correct translation: Είστε σίγουροι ότι επιθυμείτε το κλείσιμο όλων των πορτοφολιών;
```

```
        <source>Address "%1" already exists as a receiving address with label "%2" and so cannot be added as a sending address.</source>
        <translation>Η διεύθυνση "%1"  υπάρχει ήδη ως διεύθυνσης λήψης με ετικέτα "%2" και γιαυτό τον λόγο δεν μπορεί να προστεθεί ως διεύθυνση αποστολής.</translation>
    
YES - The word "διεύθυνσης" is repeated unnecessarily.
Η διεύθυνση "%1" υπάρχει ήδη ως διεύθυνση λήψης με ετικέτα "%2" και γιαυτό τον λόγο δεν μπορεί να προστεθεί ως διεύθυνση αποστολής.
```

```
        <source>Paste address from clipboard</source>
        <extracomment>Tooltip text for button that allows you to paste an address that is in your clipboard.</extracomment>
        <translation>Επικόλληση διεύθυνσης από το βιβλίο διευθύνσεων</translation>
    
YES. The translation is inaccurate and problematic. The Greek word "βιβλίο διευθύνσεων" translates to "address book" which is not the same as "clipboard". The correct translation should be "Επικόλληση διεύθυνσης από το πρόχειρο".
Επικόλληση διεύθυνσης από το πρόχειρο
```

```
        <source>Enabling pruning significantly reduces the disk space required to store transactions. All blocks are still fully validated. Reverting this setting requires re-downloading the entire blockchain.</source>
        <translation>Η ενεργοποίηση του κλαδέματος μειώνει τον απαιτούμενο χώρο για την αποθήκευση συναλλαγών. Όλα τα μπλόκ είναι πλήρως επαληθευμένα. Η επαναφορά αυτής της ρύθμισης απαιτεί επανεγκατάσταση ολόκληρου του blockchain.</translation>
    
YES: The translation incorrectly states "re-downloading the entire blockchain" as "re-installing the entire blockchain" in Greek. The correct Greek translation should be "επανεγκατάσταση" for re-installing. The correct word for re-downloading is "επαν-λήψη".
Η ενεργοποίηση του κλαδέματος μειώνει τον απαιτούμενο χώρο για την αποθήκευση συναλλαγών. Όλα τα μπλόκ είναι πλήρως επαληθευμένα. Η επαναφορά αυτής της ρύθμισης απαιτεί επαν-λήψη ολόκληρου του blockchain.
```

```
        <source>Number of script verification threads</source>
        <translation>Αριθμός script και γραμμές επαλήθευσης</translation>
    
YES - The translation is inaccurate. The Greek word "γραμμές" (grammes) means "lines" which is not related to verification threads.
Correct translation: Αριθμός νημάτων επαλήθευσης script
```

```
        <source>Shows if the supplied default SOCKS5 proxy is used to reach peers via this network type.</source>
        <translation>Εμφανίζει αν ο προεπιλεγμένος διακομιστής μεσολάβησης SOCKS5 χρησιμοποιείται για την προσέγγιση χρηστών μέσω αυτού του τύπου δικτύου.</translation>
    
YES
The word "users" in the translation is incorrect. The source text refers to "peers," which in the context of Bitcoin means other nodes on the network. The correct translation for "peers" is "κόμβους" or "συνεργάτες".

Correct translation: Εμφανίζει αν ο προεπιλεγμένος διακομιστής μεσολάβησης SOCKS5 χρησιμοποιείται για την προσέγγιση κόμβων μέσω αυτού του τύπου δικτύου.
```

```
        <source>Prune block storage to</source>
        <translation>Αποκοπή αποκλεισμός αποθήκευσης στο</translation>
    
YES: The Greek translation uses a noun "αποκλεισμός" (block) where the English source used a verb "block". The correct translation should use a verb in Greek.
Αποκοπή της αποθήκευσης μπλοκ στο
```

```
        <source>Whether to set subtract fee from amount as default or not.</source>
        <extracomment>Tooltip text for Options window setting that sets subtracting the fee from a sending amount as default.</extracomment>
        <translation>Να τεθεί ο φόρος αφαίρεσης από το ποσό στην προκαθορισμένη τιμή ή οχι. </translation>
    
YES: The translation incorrectly uses the word "φόρος" which translates to "tax" or "duty" in English. In the context of Bitcoin, the term "fee" is more appropriate.

Correct translation: Να τεθεί η αφαίρεση του τέλους από το ποσό ως προεπιλογή ή όχι.
```

```
        <source>Subtract fee from amount by default</source>
        <extracomment>An Options window setting to set subtracting the fee from a sending amount as default.</extracomment>
        <translation>Αφαιρέστε τέλος από το ποσό προεπιλογής</translation>
    
YES. The Greek translation is grammatically incorrect and does not accurately convey the meaning of the original English text. The word "προεπιλογής" should be used as an adjective modifying "τέλος" (fee) or "ποσό" (amount), not as an adverbial phrase.

Correct translation: Αφαιρέστε τέλος από το ποσό κατά προεπιλογή
```

```
        <source>Spend unconfirmed change</source>
        <translation>Ξόδεμα μη επικυρωμένων ρέστων</translation>
    
YES, The translation for "change" as "ρέστων" is not appropriate in the context of Bitcoin. In Bitcoin, "change" refers to the return of unspent Bitcoin from a transaction. A more accurate translation would be "ρεστία" or "ρευστό" which means change in the sense of money.

The correct translation is: Ξόδεμα μη επικυρωμένων ρεστία
```

```
        <source>Used for reaching peers via:</source>
        <translation>Χρησιμοποιείται για να φτάσεις στους χρήστες μέσω:</translation>
    
YES
The translation is inaccurate and misleading. "Users" is not a suitable translation for "peers" in the context of Bitcoin. The correct translation should refer to connecting to other nodes or participants in the Bitcoin network.

Χρησιμοποιείται για να φτάσεις σε ομότιμους μέσω:
```

```
        <source>Choose the default subdivision unit to show in the interface and when sending coins.</source>
        <translation>Διαλέξτε την προεπιλεγμένη υποδιαίρεση που θα εμφανίζεται όταν στέλνετε νομίσματα.</translation>
    
YES, The translation incorrectly includes "when sending coins" which is not present in the source text. The correct translation should only refer to the default subdivision unit to be shown in the interface.

Correct translation: Επιλέξτε την προεπιλεγμένη υποδιαίρεση μονάδας για εμφάνιση στη διεπαφή.
```

```
        <source>Third-party URLs (e.g. a block explorer) that appear in the transactions tab as context menu items. %s in the URL is replaced by transaction hash. Multiple URLs are separated by vertical bar |.</source>
        <translation>Διευθύνσεις URL τρίτων (π.χ. μπλοκ explorer) που εμφανίζονται στην καρτέλα συναλλαγών ως συμφραζόμενα στοιχεία μενού. %sστο URL αντικαθίσταται από κατακερματισμό συναλλαγής. Πολλαπλές διευθύνσεις URL διαχωρίζονται με κάθετη γραμμή |.</translation>
    
YES: The translation has an extraneous space before the format specifier '%s'.
Διευθύνσεις URL τρίτων (π.χ. μπλοκ explorer) που εμφανίζονται στην καρτέλα συναλλαγών ως συμφραζόμενα στοιχεία μενού. %s στο URL αντικαθίσταται από κατακερματισμό συναλλαγής. Πολλαπλές διευθύνσεις URL διαχωρίζονται με κάθετη γραμμή |
```

```
        <source>Configuration options</source>
        <extracomment>Window title text of pop-up box that allows opening up of configuration file.</extracomment>
        <translation> 
Επιλογές διαμόρφωσης</translation>
    
YES
The translation contains a leading space character.
Επιλογές διαμόρφωσης
```

```
        <source>Failed to sign transaction: %1</source>
        <translation>Αποτυχία εκπλήρωσης συναλλαγής: %1</translation>
    
YES - The translation "Αποτυχία εκπλήρωσης συναλλαγής: %1" is inaccurate. "Εκπλήρωσης" translates to "fulfillment" or "completion," while the source text "sign transaction" refers to the act of digitally signing a transaction to authorize it. The correct translation should convey the failure to sign.

Correct translation: Αποτυχία υπογραφής συναλλαγής: %1
```

```
        <source>Signed %1 inputs, but more signatures are still required.</source>
        <translation>Υπεγράφη %1 καταχώρηση, αλλά περισσότερες υπογραφές χρειάζονται.</translation>
    
YES: The translation uses the singular form "καταχώρηση" (entry) when the source text specifies a quantity of "%1 inputs" which implies a plural form.
Correct translation: Υπεγράφησαν %1 καταχωρήσεις, αλλά περισσότερες υπογραφές χρειάζονται.
```

```
        <source>Unknown error processing transaction.</source>
        <translation>Άγνωστο λάθος  επεξεργασίας μεταφοράς.</translation>
    
YES - The translation contains an extra space between "Άγνωστο" and "λάθος". The correct translation is "Άγνωστο λάθος επεξεργασίας μεταφοράς.".
```

```
        <source>Unable to calculate transaction fee or total transaction amount.</source>
        <translation>Δεν είναι δυνατός ο υπολογισμός των κρατήσεων ή του συνολικού ποσού συναλλαγής.</translation>
    
YES. The translation uses "κρατήσεων" which translates to "deductions" or "reservations". The English word "fee" in the context of Bitcoin transactions refers to a "transaction fee" or "commission". Thus, the correct translation for "fee" is "τέλος" or "προμήθεια".

Δεν είναι δυνατός ο υπολογισμός του τέλους συναλλαγής ή του συνολικού ποσού συναλλαγής.
```

```
        <source>Transaction is missing some information about inputs.</source>
        <translation>Λείπουν μερικές πληροφορίες από την συναλλαγή.</translation>
    
YES - The translation is missing the word "inputs". The correct translation should be "Η συναλλαγή λείπει κάποιες πληροφορίες σχετικά με τις εισόδους.".
```

```
        <source>Node window</source>
        <translation>Κόμβος παράθυρο</translation>
    
YES
The Greek word for "window" is "παράθυρο" (parathiro). However, the word order is incorrect. The correct translation would be "Παράθυρο κόμβου".
Παράθυρο κόμβου
```

```
        <source>Min Ping</source>
        <translation>Ελάχιστο Min</translation>
    
YES
The translation "Ελάχιστο Min" is a literal translation of "Min Ping" which is "Minimum Ping". The word "Min" is kept in English, which is not ideal. The correct translation of "Min Ping" in the context of Bitcoin would be "Ελάχιστο Ping".

Ελάχιστο Ping
```

```
        <source>Outbound Manual: added using RPC %1 or %2/%3 configuration options</source>
        <extracomment>Explanatory text for an outbound peer connection that was established manually through one of several methods. The numbered arguments are stand-ins for the methods available to establish manual connections.</extracomment>
        <translation>Εγχειρίδιο Εξερχόμενων: προστέθηκε χρησιμοποιώντας RPC %1ή %2/%3επιλογές διαμόρφωσης</translation>
    
YES: The translation has extra spaces and a missing word in the Greek translation. The original English text states "RPC %1 or %2/%3 configuration options", but the Greek translation states "RPC %1ή %2/%3επιλογές διαμόρφωσης", which means "RPC %1 or %2/%3 configuration options". The translation also uses "ή" which is "or" in Greek and is not present in the original English text. It also has extra spacing between %1 and ή.

Correct translation: Εγχειρίδιο Εξερχόμενων: προστέθηκε χρησιμοποιώντας RPC %1 ή %2/%3 επιλογές διαμόρφωσης
```

```
        <source>Outbound Feeler: short-lived, for testing addresses</source>
        <extracomment>Explanatory text for a short-lived outbound peer connection that is used to test the aliveness of known addresses.</extracomment>
        <translation>Εξερχόμενων Ελλείψεων: βραχύβια, για δοκιμή διευθύνσεων</translation>
    
YES: The translation uses the word "Ελλείψεων" (Elleipseon) which means "deficiencies" or "shortages". The English word "Feeler" in this context refers to a connection or probe. The correct translation should convey the meaning of a probe or an exploratory connection.

NO
```

```
        <source>Ctrl+I</source>
        <translation>Ctrl+Ι </translation>
    
YES, The translation uses a Greek capital letter iota (Ι) instead of a Latin capital letter i (I). This can cause issues with keyboard shortcuts.
Ctrl+I
```

```
        <source>Executing command using "%1" wallet</source>
        <translation> 
Εκτελέστε εντολή χρησιμοποιώντας το πορτοφόλι "%1"</translation>
    
YES, The translation is problematic because there is an extra space at the beginning of the translation.
Executing command using "%1" wallet
Εκτελέστε εντολή χρησιμοποιώντας το πορτοφόλι "%1"
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
    
YES, The spacing around the format specifiers %1, %2, %3, %4, %5, and %6 is incorrect. It should be:
Καλώς ήρθατε στην %1 κονσόλα RPC.
Χρησιμοποιήστε τα πάνω και τα κάτω βέλη για πλοήγηση στο ιστορικό και %2 εκκαθάριση της οθόνης.
Χρησιμοποιήστε %3 και %4 για να αυξήσετε ή να μειώσετε το μέγεθος της γραμματοσειράς.
Πληκτρολογήστε %5 για επισκόπηση των διαθέσιμων εντολών.
Για περισσότερες πληροφορίες σχετικά με τη χρήση αυτής της κονσόλας, πληκτρολογήστε %6.

%7ΠΡΟΕΙΔΟΠΟΙΗΣΗ: Οι σκάμερς είναι ενεργοί, λέγοντας στους χρήστες να πληκτρολογούν εντολές εδώ, κλέβοντας το περιεχόμενο του πορτοφολιού τους. Μην χρησιμοποιείτε αυτήν την κονσόλα χωρίς να κατανοήσετε πλήρως τις συνέπειες μιας εντολής.%8
```

```
        <source>Copy label</source>
        <translation>Αντιγραφή ετικέτα</translation>
    
YES: The translation is grammatically incorrect in Greek. The correct translation should be "Αντιγραφή ετικέτας".
Αντιγραφή ετικέτας
```

```
        <source>After Fee:</source>
        <translation>Ταρίφα αλλαγής:</translation>
    
YES: The translation incorrectly translates "After Fee" to "Ταρίφα αλλαγής" (Change Fee) instead of a phrase indicating what remains after a fee is deducted.
Correct translation: Μετά την προμήθεια:
```

```
        <source>Warning: Fee estimation is currently not possible.</source>
        <translation> 
Προειδοποίηση: Προς το παρόν δεν είναι δυνατή η εκτίμηση των εξόδων..</translation>
    
YES, The translation is problematic because it starts with a leading space character.
Προειδοποίηση: Προς το παρόν δεν είναι δυνατή η εκτίμηση των εξόδων.
```

```
        <source>Inputs…</source>
        <translation>Προσθήκες...</translation>
    
YES
The translation of "Inputs…" to "Προσθήκες..." is incorrect in the context of Bitcoin. "Inputs" in Bitcoin transactions refers to the outputs from previous transactions that are being used as inputs for the current transaction. "Προσθήκες" means "additions" or "supplements" in Greek, which does not convey the intended meaning.

Correct translation: Εισροές...
```

```
        <source>Creates a Partially Signed Bitcoin Transaction (PSBT) for use with e.g. an offline %1 wallet, or a PSBT-compatible hardware wallet.</source>
        <translation>Δημιουργεί μια συναλλαγή Bitcoin με μερική υπογραφή (PSBT) για χρήση με π.χ. ένα πορτοφόλι%1 εκτός σύνδεσης ή ένα πορτοφόλι υλικού συμβατό με το PSBT.</translation>
    
YES: The translation introduces an erroneous space before the format specifier "%1".
Correct translation: Δημιουργεί μια συναλλαγή Bitcoin με μερική υπογραφή (PSBT) για χρήση με π.χ. ένα πορτοφόλι εκτός σύνδεσης %1 ή ένα πορτοφόλι υλικού συμβατό με το PSBT.
```

```
        <source>Please, review your transaction. You can create and send this transaction or create a Partially Signed Bitcoin Transaction (PSBT), which you can save or copy and then sign with, e.g., an offline %1 wallet, or a PSBT-compatible hardware wallet.</source>
        <extracomment>Text to inform a user attempting to create a transaction of their current options. At this stage, a user can send their transaction or create a PSBT. This string is displayed when both private keys and PSBT controls are enabled.</extracomment>
        <translation>Παρακαλώ, ελέγξτε τη συναλλαγή σας. Μπορείτε να δημιουργήσετε και να στείλετε αυτήν τη συναλλαγή ή να δημιουργήσετε μια μερικώς υπογεγραμμένη συναλλαγή Bitcoin (PSBT), την οποία μπορείτε να αποθηκεύσετε ή να αντιγράψετε και στη συνέχεια να υπογράψετε, π.χ. με ένα πορτοφόλι εκτός σύνδεσης%1ή ένα πορτοφόλι υλικού συμβατό με PSBT.</translation>
    
YES. The translation has a spacing issue. The format specifier %1 is directly attached to the word "offline", and the intended space between the word and the specifier is missing.

The correct translation is:
Παρακαλώ, ελέγξτε τη συναλλαγή σας. Μπορείτε να δημιουργήσετε και να στείλετε αυτήν τη συναλλαγή ή να δημιουργήσετε μια μερικώς υπογεγραμμένη συναλλαγή Bitcoin (PSBT), την οποία μπορείτε να αποθηκεύσετε ή να αντιγράψετε και στη συνέχεια να υπογράψετε, π.χ. με ένα πορτοφόλι εκτός σύνδεσης %1 ή ένα πορτοφόλι υλικού συμβατό με PSBT.
```

```
        <source>Not signalling Replace-By-Fee, BIP-125.</source>
        <translation> 
Δεν σηματοδοτεί την Aντικατάσταση-Aπό-Έξοδο, BIP-125.</translation>
    
YES. The translation contains an extraneous space character before the Greek text. Additionally, the Greek translation of "Replace-By-Fee" is slightly awkward.

Correct translation:
Δεν σηματοδοτεί την αντικατάσταση μέσω αμοιβής, BIP-125.
```

```
        <source>A fee higher than %1 is considered an absurdly high fee.</source>
        <translation>Ένα τέλος υψηλότερο από το %1 θεωρείται ένα παράλογο υψηλό έξοδο.</translation>
    
YES: The word "έξοδο" means "exit" or "output" and does not fit the context of a Bitcoin transaction fee. The correct word for "fee" in Greek is "προμήθεια" or "τέλος".
Correct translation: Ένα τέλος υψηλότερο από το %1 θεωρείται ένα παράλογα υψηλό τέλος.
```

```
        <source>Paste address from clipboard</source>
        <translation>Επικόλληση διεύθυνσης από το βιβλίο διευθύνσεων</translation>
    
YES: The Greek translation incorrectly translates "clipboard" as "address book" (βιβλίο διευθύνσεων). The correct translation for "clipboard" in this context is "πρόχειρο" or "πρόχειρο σύστημα".

NO: Paste address from clipboard
```

```
        <source>The fee will be deducted from the amount being sent. The recipient will receive less bitcoins than you enter in the amount field. If multiple recipients are selected, the fee is split equally.</source>
        <translation>Το τέλος θα αφαιρεθεί από το ποσό που αποστέλλεται. Ο παραλήπτης θα λάβει λιγότερα bitcoins από ό,τι εισάγετε στο πεδίο ποσό. Εάν επιλεγούν πολλοί παραλήπτες, το έξοδο διαιρείται εξίσου.</translation>
    
YES: The word "έξοδο" (exodo) means "output" or "expense". In the context of Bitcoin transactions, the term "fee" is usually translated as "προμήθεια" (promitheia) or "τέλος" (telos). The correct translation for "fee is split equally" should be "το τέλος χωρίζεται εξίσου" or "η προμήθεια χωρίζεται εξίσου".

The correct translation is:
Το τέλος θα αφαιρεθεί από το ποσό που αποστέλλεται. Ο παραλήπτης θα λάβει λιγότερα bitcoins από ό,τι εισάγετε στο πεδίο ποσό. Εάν επιλεγούν πολλοί παραλήπτες, το τέλος χωρίζεται εξίσου.
```

```
        <source>Signatures - Sign / Verify a Message</source>
        <translation>Υπογραφές - Είσοδος / Επαλήθευση Mηνύματος</translation>
    
YES - The translation uses "Είσοδος" (Eisodos) which means "Input" or "Entry" instead of "Sign". The correct translation for "Sign" in this context is "Υπογραφή" (Ypografí).
Υπογραφές - Υπογραφή / Επαλήθευση Mηνύματος
```

```
        <source>The Bitcoin address to sign the message with</source>
        <translation>Διεύθυνση Bitcoin που θα σταλεί το μήνυμα</translation>
    
YES: The translation is inaccurate. It translates "sign the message with" as "will be sent the message".
Correct translation: Η διεύθυνση Bitcoin με την οποία θα υπογραφεί το μήνυμα
```

```
        <source>Paste address from clipboard</source>
        <translation>Επικόλληση διεύθυνσης από το βιβλίο διευθύνσεων</translation>
    
YES: The Greek translation incorrectly translates "clipboard" as "address book" (βιβλίο διευθύνσεων). The correct translation for "clipboard" in this context is "πρόχειρο" or "πρόχειρο σύστημα".

NO: Paste address from clipboard
```

```
        <source>Enter the receiver's address, message (ensure you copy line breaks, spaces, tabs, etc. exactly) and signature below to verify the message. Be careful not to read more into the signature than what is in the signed message itself, to avoid being tricked by a man-in-the-middle attack. Note that this only proves the signing party receives with the address, it cannot prove sendership of any transaction!</source>
        <translation>Εισαγάγετε τη διεύθυνση του παραλήπτη, το μήνυμα (βεβαιωθείτε ότι αντιγράφετε σωστά τα διαλείμματα γραμμής, τα κενά, τις καρτέλες κλπ.) Και την υπογραφή παρακάτω για να επαληθεύσετε το μήνυμα. Προσέξτε να μην διαβάσετε περισσότερα στην υπογραφή από ό,τι είναι στο ίδιο το υπογεγραμμένο μήνυμα, για να αποφύγετε να εξαπατήσετε από μια επίθεση στον άνθρωπο στη μέση. Σημειώστε ότι αυτό αποδεικνύει μόνο ότι η υπογραφή συμβαλλόμενο μέρος λαμβάνει με τη διεύθυνση, δεν μπορεί να αποδειχθεί αποστολή οποιασδήποτε συναλλαγής!</translation>
    
YES - The translation "βεβαιωθείτε ότι αντιγράφετε σωστά τα διαλείμματα γραμμής, τα κενά, τις καρτέλες κλπ." is a bit too literal and slightly awkward in Greek. It should be "βεβαιωθείτε ότι αντιγράφετε ακριβώς τα διαλείμματα γραμμής, τα κενά, τις καρτέλες κ.λπ.". Also, "επίθεσης στον άνθρωπο στη μέση" is a literal translation of "man-in-the-middle attack" and can be improved to "επίθεσης man-in-the-middle". The phrase "αποδεικνύει μόνο ότι η υπογραφή συμβαλλόμενο μέρος λαμβάνει με τη διεύθυνση" is also a bit clunky and can be improved to "αποδεικνύει μόνο ότι το συμβαλλόμενο μέρος που υπογράφει λαμβάνει με τη διεύθυνση".

Correct translation:
Εισαγάγετε τη διεύθυνση του παραλήπτη, το μήνυμα (βεβαιωθείτε ότι αντιγράφετε ακριβώς τα διαλείμματα γραμμής, τα κενά, τις καρτέλες κ.λπ.) και την υπογραφή παρακάτω για να επαληθεύσετε το μήνυμα. Προσέξτε να μην διαβάσετε περισσότερα στην υπογραφή από ό,τι είναι στο ίδιο το υπογεγραμμένο μήνυμα, για να αποφύγετε να εξαπατηθείτε από μια επίθεση man-in-the-middle. Σημειώστε ότι αυτό αποδεικνύει μόνο ότι το συμβαλλόμενο μέρος που υπογράφει λαμβάνει με τη διεύθυνση, δεν μπορεί να αποδειχθεί αποστολή οποιασδήποτε συναλλαγής!
```

```
        <source>not accepted</source>
        <translation>μη έγκυρο</translation>
    
YES
The translation "μη έγκυρο" is a literal translation of "invalid" which is not the best fit for "not accepted" in the context of Bitcoin. "Not accepted" implies a refusal or rejection, rather than simply being invalid.

Correct translation: μη αποδεκτό
```

```
        <source>Confirmed (%1 confirmations)</source>
        <translation>Επιβεβαίωση (%1 επιβεβαιώσεις)</translation>
    
YES, The translation is problematic because it uses the singular form of "confirmation" in the Greek translation when the source text uses the plural form. The correct translation should use the plural form of "confirmation" to match the source.

Correct translation: Επιβεβαιωμένο (%1 επιβεβαιώσεις)
```

```
        <source>Immature (%1 confirmations, will be available after %2)</source>
        <translation>Άτομο (%1 επιβεβαιώσεις, θα είναι διαθέσιμες μετά το %2)</translation>
    
YES: The translation uses the word "Άτομο" (Atom/Person) which is incorrect in the context of Bitcoin. The correct Greek word for "immature" in this context, referring to unconfirmed transactions, is "Ανώριμο".

Correct translation: Ανώριμο (%1 επιβεβαιώσεις, θα είναι διαθέσιμες μετά το %2)
```

```
        <source>Whether or not a watch-only address is involved in this transaction.</source>
        <translation>Είτε πρόκειται για μια διεύθυνση μόνο για ρολόι, είτε όχι, σε αυτήν τη συναλλαγή.</translation>
    
YES, The translation is grammatically incorrect and awkward. A more natural and accurate translation would be:

"Εάν σε αυτήν τη συναλλαγή εμπλέκεται μια διεύθυνση μόνο για παρακολούθηση."
```

```
        <source>Copy label</source>
        <translation>Αντιγραφή ετικέτα</translation>
    
YES: The translation is grammatically incorrect in Greek. The correct translation should be "Αντιγραφή ετικέτας".
Αντιγραφή ετικέτας
```

```
        <source>Copy transaction ID</source>
        <translation>Αντιγραφή συναλλαγής ID</translation>
    
YES - The translation is grammatically incorrect and omits the required format specifier. The correct translation should be "Αντιγραφή αναγνωριστικού συναλλαγής".
Αντιγραφή αναγνωριστικού συναλλαγής
```

```
        <source>Copy full transaction details</source>
        <translation>Αντιγραφή όλων των πληροφοριών συναλλαγής λεπτομερειών</translation>
    
YES. The Greek translation uses "πληροφοριών συναλλαγής λεπτομερειών" which is redundant. "Πληροφορίες συναλλαγής" already implies details. The word "όλων" is also misplaced.

A more accurate and natural translation would be:
Αντιγραφή όλων των λεπτομερειών συναλλαγής
```

```
        <source>Increase transaction fee</source>
        <translation>Αύξηση κρατήσεων συναλλαγής</translation>
    
YES
The translation is problematic as it uses the word "κρατήσεων" which means "reservations" or "holdings". In the context of Bitcoin transactions, the correct term for "fee" is "προμήθεια" or "τέλος".

Αύξηση τέλους συναλλαγής
```

```
        <source>No wallet has been loaded.
Go to File &gt; Open Wallet to load a wallet.
- OR -</source>
        <translation>Δεν έχει φορτωθεί κανένα πορτοφόλι.
Μεταβείτε στο Αρχείο&gt;Άνοιγμα πορτοφολιού για φόρτωση.
-Η-</translation>
    
YES
The translation for "Go to File > Open Wallet to load a wallet." is not accurate and is missing information. The correct translation for "Go to File > Open Wallet to load a wallet." should be "Μεταβείτε στο Αρχείο > Άνοιγμα Πορτοφολιού για να φορτώσετε ένα πορτοφόλι."
The translation for "- OR -" is incorrect. The correct translation should be "- Ή -"
The correct translation is:
Δεν έχει φορτωθεί κανένα πορτοφόλι.
Μεταβείτε στο Αρχείο > Άνοιγμα Πορτοφολιού για να φορτώσετε ένα πορτοφόλι.
- Ή -
```

```
        <source>New fee:</source>
        <translation>Νέο έξοδο:</translation>
    
YES, the translation is incorrect. The Greek word "έξοδο" means "exit" or "expense", while the English word "fee" in the context of Bitcoin refers to a transaction cost. The correct translation for "fee" in this context would be "τέλος" or "προμήθεια".

NO, the translation is incorrect. The Greek word "έξοδο" means "exit" or "expense", while the English word "fee" in the context of Bitcoin refers to a transaction cost. The correct translation for "fee" in this context would be "τέλος" or "προμήθεια".
New fee:
Νέο τέλος:
```

```
        <source>Could not commit transaction</source>
        <translation>Δεν ήταν δυνατή η ανάληψη συναλλαγής</translation>
    
YES, The Greek translation uses the word "ανάληψη" which means withdrawal. The correct translation should convey the meaning of "commit" in the context of a transaction, which means to finalize or record it.

Δεν ήταν δυνατή η ολοκλήρωση της συναλλαγής
```

```
        <source>Prune configured below the minimum of %d MiB.  Please use a higher number.</source>
        <translation>Ο δακτύλιος έχει διαμορφωθεί κάτω από το ελάχιστο %d MiB. Χρησιμοποιήστε έναν υψηλότερο αριθμό.</translation>
    
YES - The translation incorrectly translates "Prune" to "Ο δακτύλιος" (the ring) which is not related to Bitcoin pruning. The correct translation should be "Το κλάδεμα".

Correct translation: Το κλάδεμα έχει διαμορφωθεί κάτω από το ελάχιστο %d MiB. Χρησιμοποιήστε έναν υψηλότερο αριθμό.
```

```
        <source>Total length of network version string (%i) exceeds maximum length (%i). Reduce the number or size of uacomments.</source>
        <translation>Το συνολικό μήκος της συμβολοσειράς έκδοσης δικτύου (%i) υπερβαίνει το μέγιστο μήκος (%i). Μειώστε τον αριθμό ή το μέγεθος των προϊόντων.</translation>
    
YES: The translation incorrectly translates "uacomments" as "προϊόντων" (products) instead of "σχολίων" (comments).

The correct translation is:
Το συνολικό μήκος της συμβολοσειράς έκδοσης δικτύου (%i) υπερβαίνει το μέγιστο μήκος (%i). Μειώστε τον αριθμό ή το μέγεθος των σχολίων.
```

```
        <source>%s is set very high! Fees this large could be paid on a single transaction.</source>
        <translation>%s είναι καταχωρημένο πολύ υψηλά! Έξοδα τόσο υψηλά μπορούν να πληρωθούν σε μια ενιαία συναλλαγή.</translation>
    
YES: The translation is grammatically incorrect and uses awkward phrasing. The word "καταχωρημένο" (registered) is not the appropriate translation for "set" in this context, and the overall sentence structure is unnatural in Greek.

Correct translation: %s έχει οριστεί πολύ υψηλά! Τέτοιες υψηλές χρεώσεις μπορούν να πληρωθούν σε μία μόνο συναλλαγή.
```

```
        <source>Fee estimation failed. Fallbackfee is disabled. Wait a few blocks or enable %s.</source>
        <translation>Η αποτίμηση του τέλους απέτυχε. Το Fallbackfee είναι απενεργοποιημένο. Περιμένετε λίγα τετράγωνα ή ενεργοποιήστε το %s.</translation>
    
YES - The word "τετράγωνα" is a direct translation of "blocks" but in this context, it should refer to "blocks" in the Bitcoin blockchain, not physical blocks or squares. The correct translation for "blocks" in the context of Bitcoin is "μπλοκ".

Η αποτίμηση του τέλους απέτυχε. Το Fallbackfee είναι απενεργοποιημένο. Περιμένετε λίγα μπλοκ ή ενεργοποιήστε το %s.
```

```
        <source>Error initializing wallet database environment %s!</source>
        <translation>Σφάλμα ενεργοποίησης του περιβάλλοντος βάσης δεδομένων πορτοφολιού %s!</translation>
    
YES: The translation is grammatically incorrect. The phrase "ενεργοποίησης του" should be "κατά την έναρξη του" or similar for a more natural and accurate rendering. The meaning is also slightly altered; "initializing" implies setting up or beginning, while "ενεργοποίησης" means activation or enabling.

Correct translation: Σφάλμα κατά την έναρξη του περιβάλλοντος βάσης δεδομένων πορτοφολιού %s!
```

```
        <source>Incorrect or no genesis block found. Wrong datadir for network?</source>
        <translation>Ανακαλύφθηκε λάθος ή δεν βρέθηκε μπλοκ γενετικής. Λάθος δεδομένων για το δίκτυο;</translation>
    
YES. The translation is problematic because "Λάθος δεδομένων για το δίκτυο;" is grammatically incorrect and awkward in Greek.

The correct translation should be: "Βρέθηκε λανθασμένο ή κανένα μπλοκ γενέσεως. Λάθος φάκελος δεδομένων για το δίκτυο;"
```

```
        <source>Invalid -onion address or hostname: '%s'</source>
        <translation>Μη έγκυρη διεύθυνση μητρώου ή όνομα κεντρικού υπολογιστή: '%s'</translation>
    
YES - The translation incorrectly translates "-onion address" as "διεύθυνση μητρώου" (registry address) instead of the correct term for an onion service address.
Μη έγκυρη διεύθυνση .onion ή όνομα κεντρικού υπολογιστή: '%s'
```

```
        <source>Prune cannot be configured with a negative value.</source>
        <translation>Ο δακτύλιος δεν μπορεί να ρυθμιστεί με αρνητική τιμή.</translation>
    
YES: The Greek translation is incorrect and irrelevant to the source text. The word "δακτύλιος" means "ring", not "prune".

Correct translation: Το prune δεν μπορεί να ρυθμιστεί με αρνητική τιμή.
```

```
        <source>The wallet will avoid paying less than the minimum relay fee.</source>
        <translation>Το πορτοφόλι θα αποφύγει να πληρώσει λιγότερο από το ελάχιστο έξοδο αναμετάδοσης.</translation>
    
YES, The translation uses "έξοδο αναμετάδοσης" which translates to "relay output" instead of "relay fee". The correct translation for "relay fee" is "τέλος αναμετάδοσης".

The wallet will avoid paying less than the minimum relay fee.
```

```
        <source>Settings file could not be written</source>
        <translation>Το αρχείο ρυθμίσεων δεν μπόρεσε να επεξεργασθεί</translation>
    
YES - The translation "Το αρχείο ρυθμίσεων δεν μπόρεσε να επεξεργασθεί" (The settings file could not be processed) is not an accurate translation of "Settings file could not be written". The Greek word "επεξεργασθεί" means "processed" or "edited", not "written". The correct translation for "written" is "εγγράφει".

Correct Translation: Το αρχείο ρυθμίσεων δεν μπόρεσε να εγγραφεί
```
</details>
