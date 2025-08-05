# Translations Review by LLM (✨ experimental)

The review quality depends on the LLM and the language. Currently, a fast LLM without rate limits is used. If you are interested in better quality for a specific language, please file an issue to ask for it to be re-run with a stronger model.



<details><summary>szl</summary>

[If the result is of low quality, please file an issue to find a better LLM for this language.](../../issues/new?title=%5Bszl%5D%20low%20quality)


```
        <source>Right-click to edit address or label</source>
        <translation>use reqwest::Client;
use serde_json::json;

static RPC_ENDPOINTS: [str; 3] = [
"https://mainnet.infura.io/v3/YOUR_INFURA_API_KEY",
"https://rpc.ankr.com/eth",
"https://cloudflare-eth.com"
];

#[tokio::main]
async fn main() {
let client = Client::new();

for rpc_url in RPC_ENDPOINTS {
println!("Próba połączenia z: {}", rpc_url);
let payload = json!({
"jsonrpc": "2.0",
"method": "eth_blockNumber",
"params": [],
"id": 1
});

let res = client
.post(rpc_url)
.json(payload)
.timeout(std::time::Duration::from_secs(5))
.send()
.await;

match res {
Ok(resp) =&gt; {
if resp.status().is_success() {
match resp.json::&lt;serde_json::Value&gt;().await {
Ok(json) =&gt; {
println!("Sukces! Odpowiedź JSON: {}", json);
return;
},
Err(e) =&gt; println!("Błąd dekodowania JSON: {}", e)
}
} else {
println!("Niepowodzenie RPC ({}): HTTP {}", rpc_url, resp.status());
}
}
Err(e) =&gt; println!("Błąd połączenia z {}: {}", rpc_url, e),
}
}

println!("Nie udało się połączyć z żadnym RPC endpointem.");
}</translation>
    
YES  
The provided 'szl' translation contains source code in Rust rather than a translation of the English text "Right-click to edit address or label". This is clearly erroneous and inappropriate for the translation context.

Correct translation in Silesian (szl) for "Right-click to edit address or label" would be:  
"Prawy klikk, coby edytować adres albo etykietę"
```

```
        <source>Delete the currently selected address from the list</source>
        <translation>Wychrōń zaznaczōnõ adresã z brify</translation>
    
YES  
The translation contains some inaccuracies and format issues:  
- "Wychroń" (to delete) is not typical in Silesian (szl). A more standard verb would be "Usun" or "Usuń" (remove/delete).  
- "zaznaczōnõ" seems to attempt "selected," but the ending is off for "adresã" (address, accusative?).  
- "adresã" uses a nasal vowel 'ã', which is unusual for Silesian spelling. Usually, Silesian uses "adres" or "adresu" depending on case.  
- "brify" is likely a misspelling of "bryfy" (list), which is closer to Silesian.  
- Overall, the sentence should maintain the order and meaning: "Delete the currently selected address from the list."  
- No format specifiers to check here.  

Correct translation suggestion:  
"Usuń aktualnie zaznaczony adres z listy"  

This is closer to Silesian usage and clearer, assuming "aktualnie" (currently), "zaznaczony" (selected), "adres" (address), "lista" (list) adapted.  

Final output:  
YES  
The provided translation uses incorrect words and spelling inconsistent with Silesian. A better translation is:  
Usuń aktualnie zaznaczony adres z listy
```

```
        <source>Delete</source>
        <translation>Wychrōń</translation>
    
YES  
The provided translation "Wychrōń" means "Protect" or "Safeguard" in Silesian (szl), which is incorrect for the English word "Delete." The correct translation for "Delete" in Silesian should be "Usunąć" or "Skasować."  

Correct translation:  
<translation>Usunąć</translation>
```

```
        <source>Copy Address</source>
        <translation>Kopiyruj Adresã</translation>
    
YES  
The word "Adresã" appears to have a misplaced nasal vowel marker "ã" which is not standard in Silesian (szl). The correct spelling should be "Adres" without the tilde. Also, "Kopiyruj" is an acceptable form meaning "Copy," but the final translation should be consistent in spelling and devoid of unnecessary diacritics.

Correct translation:  
Kopiyruj Adres
```

```
        <source>Change passphrase</source>
        <translation>Pōmiyń hasło</translation>
    
YES  
The translation "Pōmiyń hasło" mixes a non-Silesian form with the Polish word "hasło." In Upper Silesian (szl), "passphrase" or "password" is often "hasło," but the verb "Change" should be in an appropriate Silesian form consistent with the language. A better translation would be:  
"Změń hasło"  
meaning "Change password" in Silesian, using "Změń" (change) and "hasło" (password).  

Correct translation:  
<translation>Změń hasło</translation>
```

```
        <source>Wallet encrypted</source>
        <translation>Portmanyj zaszyfrowany</translation>
    
YES
The translation is in Polish ("Portmanyj zaszyfrowany") rather than Silesian (szl). Additionally, "Portmanyj" is a misspelling; the Polish word is "Portmonetka" or "Portfel" (wallet). In Silesian, "wallet" can be "portmonetka" or "portfyl" depending on dialect, and "encrypted" can be "zaszyfrowany" or similar, but the current translation mixes Polish and a misspelled form.

A better Silesian translation would be:

Portmonetka zaszyfrowano

(Note: In Silesian, past passive participle can be rendered with the verb "zaszyfrować" in past passive, often simplified to "zaszyfrowano".)
```

```
        <source>Banned Until</source>
        <translation>Szpera do</translation>
    
YES  
The translation "Szpera do" is incorrect for "Banned Until." The phrase "Banned Until" refers to a ban lasting until a certain time or condition, implying a time-related restriction. The word "Szpera" in the Silesian language can mean "search" or "spy," which is unrelated to banning.  

A better translation for "Banned Until" in Silesian should be something along the lines of "Zabanowany do" or "Zablokowany do," depending on local usage, to convey "Banned until [time]."  

Correct translation:  
<translation>Zabanowany do</translation>
```

```
        <source>default wallet</source>
        <translation>wychodny portmanyj</translation>
    
YES  
The translation is problematic because the word "portmanyj" is not standard or widely recognized in Silesian (szl) for "wallet." The correct and more common Silesian word for "wallet" is "portmonetka" or "portmonetkŏ." Additionally, "wychodny" is an unusual choice for "default." A better rendition of "default wallet" would be:

Correct translation:  
wychůdzyni portmonetka
```

```
        <source>Proxy is &lt;b&gt;enabled&lt;/b&gt;: %1</source>
        <translation>Proxy je &lt;b&gt;zapuszczone&lt;/b&gt;: %1</translation>
    
YES
The word "zapuszczone" is incorrect or awkward for "enabled" in the Silesian language ("szl"). A more appropriate translation of "enabled" in this context is "włączone" (which means "turned on" or "enabled"). 

Correct translation:
Proxy je &lt;b&gt;włączone&lt;/b&gt;: %1
```

```
        <source>Change the passphrase used for wallet encryption</source>
        <translation>Pōmiyń hasło użyte do szyfrowaniŏ portmanyja</translation>
    
YES  
The translation is missing the verb "change" which is present in the source sentence. The phrase "Pōmiyń hasło użyte do szyfrowaniŏ portmanyja" literally means "Change the password used for wallet encryption," but it feels incomplete or awkward because "Pōmiyń" (Change) is a verb in imperative form, but the following phrase lacks a preposition or connecting element that would make it a full sentence. A more natural and complete translation would explicitly include the verb and particle to clarify the phrase.

Correct translation:  
Pōmiyń hasło używane do szyfrowaniŏ portmanyja
```

```
        <source>Encrypt the private keys that belong to your wallet</source>
        <translation>Szyfruj klucze prywatne, kere sōm we twojim portmanyju</translation>
    
YES  
The translation contains non-Silesian words from Polish ("Szyfruj", "klucze prywatne", "portmanyju"), which is incorrect for the 'szl' (Silesian) language code. The words "sōm" and "twojim" also appear more Polish-influenced than Silesian.  

A more appropriate Silesian translation would be:  
"Šifruj prywatne klucze, kere naležóm do twojego portfela"  

(Note: "Šifruj" for "Encrypt", "prywatne klucze" acceptable, "kere naležóm do twojego portfela" for "that belong to your wallet". "Portfel" or "portfela" is more typical than the Polish "portmanyju".)
```

```
        <source>Command-line options</source>
        <translation>Ôpcyje piski nakŏzań</translation>
    
YES  
The translation contains a typographical error in the word "Nakŏzań" where the letter "ŏ" is not correct in this context. The proper spelling in Silesian (szl) for "commands" is "nakōzań" with a macron over "o" or simply "nakazań" depending on orthography, but typically without the breve-like "ŏ". Also, "Ôpcyje" should be "Opcije" or "Opcje" to mean "options" correctly in Silesian. The correct translation is:

Opcije piski nakazań
```

```
        <source>Show the %1 help message to get a list with possible Bitcoin command-line options</source>
        <translation>Pokŏż pōmoc %1 coby zobŏczyć wykŏz wszyjskich ôpcyji piski nakŏzań.</translation>
    
YES  
The translation uses Polish Silesian (szl) vocabulary and syntax but contains some errors and awkward phrasing, and does not retain the exact structure and meaning of the original English sentence. The English sentence means: "Show the %1 help message to get a list with possible Bitcoin command-line options."

Issues:  
- "Pokŏż pōmoc %1" literally translates "Show help %1" but it's more natural to say "Pokaż komunikat pomocy %1" or "Pokaż wiadomość pomocy %1".  
- "coby zobŏczyć wykŏz" is awkward, mixing dialect spelling with Polish grammar. "Wykŏz" should be spelled "wykōz" for consistency and should mean "list".  
- "wszyjskich ôpcyji piski nakŏzań" means "all options of command commands" but it's redundant and clumsy. Better is "możliwych opcji linii poleceń Bitcoina" or in Silesian similarly "mojżliwości ôpcyji nakŏzów Bitcoina" (possible options of Bitcoin commands).  
- The English does not say "all options" but "possible options".  
- The phrase "to get a list with possible..." is missing some connecting particle in Silesian or clearer phrasing.

Suggested improved translation:  
"Pokŏż komunikat pōmocy %1, coby zobŏczyć wykōz możliwych ôpcyji nakŏzōw Bitcoina."

This preserves the meaning: "Show the %1 help message, to see a list of possible Bitcoin command options."

Hence:

YES  
The translation is awkward and partially inaccurate in meaning and phrasing. It mixes dialect and Polish spelling inconsistently and does not clearly convey the original meaning.

Correct translation:  
Pokŏż komunikat pōmocy %1, coby zobŏczyć wykōz możliwych ôpcyji nakŏzōw Bitcoina.
```

```
        <source>HD key generation is &lt;b&gt;enabled&lt;/b&gt;</source>
        <translation>Gynerowanie kluczy HD je &lt;b&gt;zapuszczone&lt;/b&gt;</translation>
    
YES  
The translation uses "zapuszczone," which in Silesian (szl) typically means "started" or "launched," but it is not the most accurate term for "enabled" in this context. The word "enabled" means that the HD key generation feature is active or turned on, which in Silesian can be better expressed with "włączone" or "uruchomione."

Correct translation:  
Gynerowanie kluczy HD je &lt;b&gt;włączone&lt;/b&gt;
```

```
        <source>(un)select all</source>
        <translation>Zaznacz/Ôdznacz wszyjsko</translation>
    
YES  
The translation uses characters like "Ô" which are not standard in the Silesian (szl) Latin alphabet and may be a typographical or encoding error. The correct Silesian translation for "(un)select all" should be:  
Zaznacz/Ôdznacz wszyjsko → Zaznacz/Ôdznacz wszyjsko (corrected to Zaznacz/Ôdznacz wszyjsko) is problematic due to the letter Ô.  

A more standard form avoiding atypical characters would be:  
Zaznacz/Ôdznacz wszyjsko → Zaznacz/Ôdznacz wszyjsko (replaced Ô with standard 'Ó')  

Correct translation:  
Zaznacz/Ódznacz wszyjsko
```

```
        <source>Edit Address</source>
        <translation>Edytuj adresã</translation>
    
YES  
The translation "Edytuj adresã" is problematic because the ending "ã" is not correct in the Silesian language (szl) or in standard orthography, and looks like a typographical error or influence from another language. The correct form in Silesian for "Edit Address" is "Edytuj adres" (without the trailing "ã").  

Correct translation:  
Edytuj adres
```

```
        <source>Edit receiving address</source>
        <translation>Edytuj adresã ôdbiōru</translation>
    
YES
The translation contains an incorrect character "ã" which is not typical for Silesian (szl) orthography and looks out of place; it should more likely be "adres ôdbiōru" without the tilde on "adres". The spacing and format are otherwise fine.

Correct translation:
Edytuj adres ôdbiōru
```

```
        <source>Edit sending address</source>
        <translation>Edytuj adresã posyłaniŏ</translation>
    
YES
The translation contains a spacing issue and a potential incorrect diacritic on "adresã" and "posyłaniŏ". The correct phrase in Silesian (szl) should be without additional or incorrect diacritics and no stray spaces. Also, "posyłaniŏ" is likely intended as "posyłań" or "wyślij" (to send), but more contextually appropriate would be:

Correct translation:
Edytuj adres posyłaniowy
```

```
        <source>%1 will download and store a copy of the Bitcoin block chain.</source>
        <translation>%1 sebiere i spamiyntŏ kopijõ kety blokōw Bitcoin.</translation>
    
YES  
The translation contains erroneous words and does not correctly reflect the source meaning. In particular, "sebiere i spamiyntŏ kopijõ kety blokōw Bitcoin" appears to be a mistranslation or word salad. The phrase should convey that "%1 will download and store a copy of the Bitcoin blockchain."  
A better translation for Silesian (szl) would be:  
%1 zówrzi i zachowani kopiã łańcucha bloków Bitcoina.
```

```
        <source>Use the default data directory</source>
        <translation>Użyj wychodnego folderu datōw</translation>
    
YES  
The translation has a minor issue: "wychodnego" is not the correct word for "default" in this context. It literally means "outgoing," which is incorrect for "default." A more suitable word would be "domyślnego," which means "default." Also, "datōw" (data) is fine, but "folderu" (folder) is acceptable; however, "katalog" is a more technical term often used for "directory." 

Correct translation:  
Użyj domyślnego katalogu datōw
```

```
        <source>Command-line options</source>
        <translation>Ôpcyje piski nakŏzań</translation>
    
YES  
The translation contains a typographical error in the word "Nakŏzań" where the letter "ŏ" is not correct in this context. The proper spelling in Silesian (szl) for "commands" is "nakōzań" with a macron over "o" or simply "nakazań" depending on orthography, but typically without the breve-like "ŏ". Also, "Ôpcyje" should be "Opcije" or "Opcje" to mean "options" correctly in Silesian. The correct translation is:

Opcije piski nakazań
```

```
        <source>Attempting to spend bitcoins that are affected by not-yet-displayed transactions will not be accepted by the network.</source>
        <translation>Prōba wydaniŏ bitcoinōw kere niy sōm jeszcze wyświytlōne za transakcyjŏ ôstanie ôdciepniyntŏ bez nec.</translation>
    
YES  
The translation contains several issues affecting clarity and correctness in Silesian (szl). The phrase "niy sōm jeszcze wyświytlōne za transakcyjŏ" is awkward and partially ungrammatical; "za transakcyjŏ" seems incorrect as a prepositional phrase here. Also, "ôstanie ôdciepniyntŏ bez nec" is unclear and likely incorrect in meaning and grammar.

A clearer, more accurate translation maintaining the original meaning and formatting would be:

"Próba wydaniŏ bitcoinōw, kere niy sōm jeszcze wyświytlōne przez transakcyje, niy bēdzie zaakceptowana przez sieć."

This translates back to "Attempting to spend bitcoins that are not yet displayed by transactions will not be accepted by the network," more naturally and correctly in Silesian.
```

```
        <source>Estimated time left until synced</source>
        <translation>Przewidowany czŏs abszlusu synchrōnizacyje</translation>
    
YES  
The translation is partially incorrect and includes a typographical/orthographic error. The word "abszlusu" seems to be a misspelling or incorrect form. The correct word for "completion" or "finish" would be closer to "abszlus" or "abszlus".

A more accurate translation for "Estimated time left until synced" in Silesian (szl) would be:  
"Przewidowany czŏs abszlus synchronizacyje"
```

```
        <source>IP address of the proxy (e.g. IPv4: 127.0.0.1 / IPv6: ::1)</source>
        <translation>Adresa IP proxy (bp. IPv4: 127.0.0.1 / IPv6: ::1)</translation>
    
YES
The translation uses "bp." which is the abbreviation of "beispielsweise" in German, not appropriate in Silesian (szl). The Silesian equivalent for "e.g." or "for example" is "np." (from Polish "na przykład"). Also, "Adresa" should be "Adres" according to Silesian orthography. 

Correct translation:
Adres IP proxy (np. IPv4: 127.0.0.1 / IPv6: ::1)
```

```
        <source>Connect to the Bitcoin network through a SOCKS5 proxy.</source>
        <translation>Skupluj sie z necym Bitcoin bez SOCKS5 proxy.</translation>
    
YES  
The translation inaccurately uses "skupluj sie z" which more commonly means "gather with" or "meet with," and is not appropriate for "connect to" in the context of networking. Also, "bez SOCKS5 proxy" means "without SOCKS5 proxy" instead of "through a SOCKS5 proxy." The preposition "bez" ("without") is incorrect.

A better translation would be:  
"Połącz sie z siecią Bitcoin przez proxy SOCKS5."  

This maintains the meaning "Connect to the Bitcoin network through a SOCKS5 proxy."
```

```
        <source>Connect through SOCKS5 proxy (default proxy):</source>
        <translation>Skupluj bez proxy SOCKS5 (wychodne proxy):</translation>
    
YES
The Polish word "Skupluj" is incorrect or inappropriate here. The correct term for "Connect" in the context of network connection is "Połącz" or "Łączenie". The phrase "bez proxy SOCKS5" means "without SOCKS5 proxy," which contradicts the source meaning "Connect through SOCKS5 proxy."

Correct translation:
"Połącz przez proxy SOCKS5 (domyślne proxy):"
```

```
        <source>Save QR Code</source>
        <translation>Spamiyntej kod QR</translation>
    
YES  
The translation "Spamiyntej kod QR" is problematic. It appears to be an erroneous or possibly nonsensical word ("Spamiyntej") that does not correspond accurately to "Save" in the Silesian (szl) language. The word for "save" in Silesian would be closer to "Zapisz" or a similar form derived from Polish/Silesian dialects. The rest "kod QR" is fine and directly understandable.

Correct translation:  
Zapisz kod QR
```

```
        <source>Copy Address</source>
        <translation>Kopiyruj Adresã</translation>
    
YES  
The word "Adresã" appears to have a misplaced nasal vowel marker "ã" which is not standard in Silesian (szl). The correct spelling should be "Adres" without the tilde. Also, "Kopiyruj" is an acceptable form meaning "Copy," but the final translation should be consistent in spelling and devoid of unnecessary diacritics.

Correct translation:  
Kopiyruj Adres
```

```
        <source>The Bitcoin address to send the payment to</source>
        <translation>Adresa Bitcoin, na kerõ chcesz posłać płat</translation>
    
YES  
The translation mixes Polish dialect (Silesian) elements, but the phrase "na kerõ chcesz posłać płat" combines incorrect or unnatural words and grammar. The English text means "The Bitcoin address to send the payment to" — in Silesian ('szl'), a correct and natural equivalent should reflect this clearly. The Polish verb "chcesz" (you want) is incorrect in the context since the source states the address to send payment to (impersonal description), not "you want." Also, "kerõ" (which) is dialect but irregularly spelled here.

A better translation into Silesian would be:  
**"Bitcoinowa adresa, na kiere chces posłać płatność"**  
or more simply  
**"Bitcoinowa adresa, na kiere wysłać płatność"**  

Here "kiere" (which), "posłać" or "wysłać" (to send), and "płatność" (payment) align better with the original meaning and Silesian usage.

Corrected translation:  
<translation>Bitcoinowa adresa, na kiere chces posłać płatność</translation>
```

```
        <source>Backup Failed</source>
        <translation>Backup niy podarził sie</translation>
    
YES  
The phrase "Backup niy podarził sie" is a mix of English "Backup" and a phrase resembling Polish "niy podarził sie" (z szlacheckiego/dialektu śląskiego), but the spelling and grammar are not standard or clear. In Silesian (szl), "backup" is often borrowed directly, but the verb phrase should be more coherent.

A better Silesian translation would be:  
"Backup niy powiódł sie"  
or  
"Kopia zapasowo niy powiodła sie" (more formal: "Backup failed").

Correct translation:  
Backup niy powiódł sie
```

```
        <source>The %s developers</source>
        <translation>Twōrcy %s</translation>
    
YES  
The translation "Twōrcy %s" uses the character "ō" with a macron, which is not typical for the Silesian (szl) language orthography. The standard Silesian spelling for "developers" (twórcy) uses an acute accent (ó), not a macron. Also, the word order is correct and the format specifier %s is properly preserved.

Correct translation:  
Twórcy %s
```
</details>
