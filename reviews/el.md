# Translations Review by LLM (✨ experimental)

The review quality depends on the LLM and the language. Currently, a fast LLM without rate limits is used. If you are interested in better quality for a specific language, please file an issue to ask for it to be re-run with a stronger model.



<details><summary>el</summary>

[If the result is of low quality, please file an issue to find a better LLM for this language.](../../issues/new?title=%5Bel%5D%20low%20quality)


<!-- cache_translation_check_el_421e649cbdeb9bc2c18c2aa4eb6ca274448b098165e4f346865bdbd3db2ad776 -->
```
        <source>Custom…</source>
        <translation>Προσαρμογή:</translation>
    
ERR
The translation uses the colon (:) instead of the ellipsis (…). The ellipsis must be kept to match the original meaning and standard Greek UI conventions.

Correct translation:
Προσαρμογή…
```

<!-- cache_translation_check_el_4fe7b435f758c0705931f80459555d2b992ab9fcdff7b319d46e2fce4dbe88d5 -->
```
        <source>Automatically open the Bitcoin client port on the router. This only works when your router supports PCP or NAT-PMP and it is enabled. The external port could be random.</source>
        <translation>Ανοίξτε αυτόματα τη πόρτα του Bitcoin client στο router. Αυτό λειτουργεί μόνο όταν το router σας υποστηρίζει NAT-PMP και είναι ενεργοποιημένο. Η εξωτερική πόρτα μπορεί να είναι τυχαία.</translation>
    
ERR
The translation omits "PCP" from the phrase "supports PCP or NAT-PMP", translating only "NAT-PMP". Also, "client" could be better translated as "πελάτη" in this context for clarity, and the article before "πόρτα" should be "την" instead of "τη" (which is a mistake when the following word starts with a consonant). Furthermore, "το router" could be in Greek: "το δρομολογητή". However, the translation is mostly understandable.

Correct translation:
Ανοίγει αυτόματα την πόρτα του πελάτη Bitcoin στον δρομολογητή. Αυτό λειτουργεί μόνο όταν ο δρομολογητής σας υποστηρίζει PCP ή NAT-PMP και είναι ενεργοποιημένο. Η εξωτερική πόρτα μπορεί να είναι τυχαία.
```

<!-- cache_translation_check_el_ede19ec8d1e65c52ed129374272d8b028e59f1f52405eb260350be7380b21e88 -->
```
        <source>Hide Peers Detail</source>
        <translation>Απόκρυψη Λεπτομερειών Χρηστών</translation>
    
ERR
The English "Hide Peers Detail" should refer to peers/connected nodes on the Bitcoin network, not users. The Greek "Χρηστών" means "users", which is incorrect here. Furthermore, "Λεπτομερειών" is correct for "Detail(s)" (although "Λεπτομέρειες" is usually plural), but the peer/user confusion is significant.

Correct translation:
Απόκρυψη λεπτομερειών ομότιμων (or Απόκρυψη λεπτομερειών peers)
```

<!-- cache_translation_check_el_3c85aa2076602054ad68f38e753f3b6198047b7fbf1cd0947929af899d97949d -->
```
        <source>Outbound connections restricted to Tor (-onlynet=onion) but the proxy for reaching the Tor network is not provided: none of -proxy, -onion or -listenonion is given</source>
        <translation>Εξερχόμενες συνδέσεις περιορίζονται στο Tor (-onlynet=onion) αλλά ο proxy για πρόσβαση στο Tor δίκτυο δεν ορίστικε: με ένα από τα -proxy, -onion ή -listenonion</translation>
    
ERR
The translation is understandable but has grammatical issues and does not fully reflect the original structure. The phrase "δεν ορίστικε" should be "δεν παρέχεται" or "δεν έχει δοθεί", and the part "none of -proxy, -onion or -listenonion is given" is not translated correctly; it means that none are provided, but the translation says "με ένα από τα..." ("with one of...") which is the opposite.

Correct translation:
Εξερχόμενες συνδέσεις περιορίζονται στο Tor (-onlynet=onion), αλλά δεν παρέχεται διακομιστής μεσολάβησης (proxy) για πρόσβαση στο δίκτυο Tor: δεν έχει δοθεί κανένα από τα -proxy, -onion ή -listenonion
```

<!-- cache_translation_check_el_fd10445bb0f5d7b29bb6ca34bd372cbc0b7fa3258aaf286b2f65d1ea18452d9d -->
```
        <source>Replaying blocks…</source>
        <translation>Επανεκτέλεση των block…</translation>
    
ERR
The translation uses the English word "block" instead of the Greek equivalent. Also, "Επανεκτέλεση των block" is a bit unnatural; a better translation would be "Επανεκτέλεση των μπλοκ…" or "Επανεκτελούνται τα μπλοκ…"

Correct translation:
Επανεκτέλεση των μπλοκ…
```

<!-- cache_translation_check_el_c42a58ab6e73b73bc7cd6d76d1ac6758b0eb3dce6991a143a8c392b7317905a3 -->
```
        <source>Unable to parse -maxuploadtarget: '%s'</source>
        <translation>Μη έγκυρη τιμή για -maxuploadtarget: '%s'</translation>
    
ERR
The translation changes the meaning; the original says "Unable to parse," while the translation means "Invalid value for." The parsing failure may not always be due to an invalid value.

Correct translation:
Αδύνατη η ανάλυση του -maxuploadtarget: '%s'
```
</details>

Number of issues: 6.
