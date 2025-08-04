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
    
YES: The translation is not a translation of the source text, but rather a Rust code snippet.
NO: Right-click to edit address or label
```

```
        <source>Create a new address</source>
        <translation>Zrychtuj nowõ adresã</translation>
    
YES. The translation is inaccurate and grammatically incorrect. The verb "Zrychtuj" is not a common or appropriate verb for "create" in this context, and the noun "adresã" is also incorrect.

Correct translation: Stwórz nowy adres
```

```
        <source>Close</source>
        <translation>Zawrzij</translation>
    
YES: The provided translation is incorrect. In the context of user interfaces or forms, "Close" typically means to dismiss or exit an element, while "Zawrzij" in Polish means "Conclude" or "Resume". The correct Polish translation for "Close" in this context would be "Zamknij".
Zamknij
```

```
        <source>Delete the currently selected address from the list</source>
        <translation>Wychrōń zaznaczōnõ adresã z brify</translation>
    
YES - The word "Wychrōń" means "Choose" or "Select" in Polish, not "Delete". The correct translation should be "Usiyōmō zaznaczōnõ adresã z brify".
YES - Wychrōń zaznaczōnõ adresã z brify - "Usiyōmō zaznaczōnõ adresã z brify"
```

```
        <source>Enter address or label to search</source>
        <translation>Wkludź adresã abo etyketã coby wyszukać</translation>
    
YES, the translation is problematic. The 'ã' character is not a standard character in the Polish language (which Silesian is closely related to, but this rendering is unusual and likely incorrect). It appears to be an attempt to handle nasal vowels incorrectly.

Correct translation: Wkludź adres albo etykietę coby wyszukać
```

```
        <source>Delete</source>
        <translation>Wychrōń</translation>
    
YES, The translation of "Delete" to "Wychrōń" is incorrect. "Wychrōń" in Polish means "Protect" or "Save". The correct translation for "Delete" in Polish is "Usuń".
NO
```

```
        <source>Choose the address to receive coins with</source>
        <translation>Ôbier adresã, na kerõ chcesz dostać mōnety</translation>
    
YES - The translation uses "Ôbier" which is not a standard Polish word. It should be "Wybierz" or "Obierz". The word "adresã" also contains an incorrect diacritic.
Correct translation: Wybierz adres, na który chcesz dostać monety.
```

```
        <source>Copy Address</source>
        <translation>Kopiyruj Adresã</translation>
    
YES, The translation uses an incorrect character in the word "Kopiyruj". It should be "Kopiyruj".

The correct translation is:
Kopiyruj Adresã
```

```
        <source>Export Address List</source>
        <translation>Eksportuj wykŏz adres</translation>
    
YES, The Polish word "wykaz" is grammatically incorrect in this context. It should be "wykaz" or "listę".
Eksportuj listę adresów
```

```
        <source>There was an error trying to save the address list to %1. Please try again.</source>
        <extracomment>An error message. %1 is a stand-in argument for the name of the file we attempted to save to.</extracomment>
        <translation>Przitrefiōł sie feler w czasie spamiyntowaniŏ brify adres do %1. Proszã sprōbować zaś.</translation>
    
YES, The translation contains an erroneous word "spamiyntowaniŏ" which is likely a mistranslation of "saving" or "saving the address list". The correct translation for "saving" in this context would be "zapisywaniŏ".

NO, Przitrefiōł sie feler w czasie zapisywaniŏ brify adres do %1. Proszã sprōbować zaś.
```

```
        <source>Enter passphrase</source>
        <translation>Wkludź hasło</translation>
    
UNK_LANG
```

```
        <source>Unlock wallet</source>
        <translation>Ôdszperuj portmanyj.</translation>
    
YES, The translation is problematic due to an incorrect word choice. The word "portmanyj" is not a recognized word in Polish or Silesian languages for "wallet". The correct translation should use a word like "portfel" (Polish) or a suitable Silesian equivalent.

The translation is "Ôdszperuj portmanyj."
The correct translation should be "Odblokuj portfel." or "Odblokuj sakwoj." in Silesian.

NO
```

```
        <source>Change passphrase</source>
        <translation>Pōmiyń hasło</translation>
    
YES, the translation is problematic because the word "pōmiyń" is not a standard or recognizable word in Polish, which is the likely language intended by "szl" given the context of common Slavic languages. The correct translation for "Change passphrase" in Polish is "Zmień hasło".

NO
```

```
        <source>Confirm wallet encryption</source>
        <translation>Przituplikuj szyfrowanie portmanyja</translation>
    
YES, The translation is problematic because it is not accurate. The correct translation for "Confirm wallet encryption" in Polish (which is the language of the translation, not 'szl') would be "Potwierdź szyfrowanie portfela". The provided translation "Przituplikuj szyfrowanie portmanyja" uses incorrect words and grammar.
Potwierdź szyfrowanie portfela
```

```
        <source>Are you sure you wish to encrypt your wallet?</source>
        <translation>Na isto chcesz zaszyfrować swōj portmanyj?</translation>
    
YES - The translation uses a dialect of Polish that is not standard and might be confusing for a general audience. The use of "swōj portmanyj" instead of the more common "swój portfel" or "twój portfel" is a dialectal variation.
NO - Are you sure you wish to encrypt your wallet?
```

```
        <source>Wallet encrypted</source>
        <translation>Portmanyj zaszyfrowany</translation>
    
YES
The translation is problematic because it uses the word "Portmanyj" which is not a recognized word in Polish (the closest language to Szl). It appears to be a misspelling or an invented word. The correct translation should convey that the wallet is encrypted.

NO
Wallet encrypted
Portmonetka zaszyfrowana
```

```
        <source>IP/Netmask</source>
        <translation>IP/Maska necu</translation>
    
YES, The Polish translation for "IP/Netmask" is "IP/Maską sieci". The provided translation "IP/Maska necu" is not a correct or meaningful Polish phrase.
Correct translation: IP/Maską sieci
```

```
        <source>Banned Until</source>
        <translation>Szpera do</translation>
    
YES, The translation is inaccurate and nonsensical. "Szpera do" in Polish translates to "rummage until" or "dig until" which is not related to "Banned Until" in the context of Bitcoin.
Correct translation: Zakazany do
```

```
        <source>Enter a Bitcoin address (e.g. %1)</source>
        <translation>Wkludź adresã Bitcoin (bp. %1)</translation>
    
YES: The translation uses a cedilla on the 'a' in "adres" ("adresã"), which is incorrect for Polish. The correct translation should not have this character.
Correct translation: Wkludź adres Bitcoin (bp. %1)
```

```
        <source>default wallet</source>
        <translation>wychodny portmanyj</translation>
    
YES, The translation is inaccurate. The provided translation "wychodny portmanyj" seems to be a misinterpretation or a very literal translation that doesn't convey the intended meaning of "default wallet" in the context of Bitcoin. In Polish, a more appropriate translation for "default wallet" would be "domyślny portfel" or "domyślny portfelik".

NO
```

```
        <source>Quit application</source>
        <translation>Zawrzij aplikacyjõ</translation>
    
YES, The translation contains a misspelling. The correct translation is "Zawrzyj aplikację".
```

```
        <source>Wallet:</source>
        <translation>Portmanyj:</translation>
    
YES, The word "Portmanyj" is not a valid translation for "Wallet" in the context of Bitcoin. The correct translation would be "Peńyonka".
YES, Wallet: Portmanyj
```

```
        <source>Proxy is &lt;b&gt;enabled&lt;/b&gt;: %1</source>
        <translation>Proxy je &lt;b&gt;zapuszczone&lt;/b&gt;: %1</translation>
    
YES: The Polish word "zapuszczone" translates to "run-down" or "neglected," which is not the intended meaning of "enabled" in the context of a proxy server. The correct translation should convey that the proxy is active or switched on.
Proxy je &lt;b&gt;povolené&lt;/b&gt;: %1
```

```
        <source>Change the passphrase used for wallet encryption</source>
        <translation>Pōmiyń hasło użyte do szyfrowaniŏ portmanyja</translation>
    
YES - The translation contains a misspelling. The Polish word for "passphrase" is "hasło", but the translated word is "hasłó".

Correct translation: Pōmiyń hasło użyte do szyfrowaniŏ portmanyja
```

```
        <source>Encrypt the private keys that belong to your wallet</source>
        <translation>Szyfruj klucze prywatne, kere sōm we twojim portmanyju</translation>
    
YES, The translation contains an erroneous word "kere" which does not belong in the sentence. The correct translation should be "Szyfruj klucze prywatne, kiere sōm we twojim portmanyju".
```

```
        <source>Command-line options</source>
        <translation>Ôpcyje piski nakŏzań</translation>
    
YES - The translation uses a German-sounding word ("Ôpcyje") which is not Polish. The correct Polish word for "options" is "Opcje". Also, "piski nakŏzań" is not a correct translation for "command-line". The correct translation would be "linia komend" or "wiersza poleceń".

Correct translation: Opcje linii komend
```

```
        <source>Show the %1 help message to get a list with possible Bitcoin command-line options</source>
        <translation>Pokŏż pōmoc %1 coby zobŏczyć wykŏz wszyjskich ôpcyji piski nakŏzań.</translation>
    
YES - The translation is not entirely accurate. It should specify "Bitcoin command-line options" and not "Bitcoin command line options".

Correct translation: Pokŏż pōmoc %1 coby zobŏczyć wykŏz wszyjskich ôpcyji piski nakŏzań Bitcoin.
```

```
        <source>Wallet: %1
</source>
        <translation>Portmanyj: %1
</translation>
    
YES, The word "Portmanyj" is likely a misspelling or an invented word. In the context of Bitcoin wallets, "wallet" is usually translated to "peňaženka" in Slovak or similar terms in other Slavic languages. A direct and accurate translation would be "Peňaženka: %1".
Portmanyj: %1
```

```
        <source>HD key generation is &lt;b&gt;enabled&lt;/b&gt;</source>
        <translation>Gynerowanie kluczy HD je &lt;b&gt;zapuszczone&lt;/b&gt;</translation>
    
YES, The translation incorrectly uses "zapuszczone" which means "neglected" or "overgrown" instead of "enabled" or "activated". The correct translation should use a term that signifies activation or readiness.
Gynerowanie kluczy HD je &lt;b&gt;włączone&lt;/b&gt;
```

```
        <source>HD key generation is &lt;b&gt;disabled&lt;/b&gt;</source>
        <translation>Gynerowanie kluczy HD je &lt;b&gt;zastawiōne&lt;/b&gt;</translation>
    
YES - The Polish word for "disabled" is "wyłączony" or "nieaktywny", not "zastawiony", which means "pawned" or "mortgaged". The correct translation should be: "Gynerowanie kluczy HD je &lt;b&gt;wyłączōne&lt;/b&gt;".
```

```
        <source>(un)select all</source>
        <translation>Zaznacz/Ôdznacz wszyjsko</translation>
    
YES, The Polish translation uses an archaic form of the letter "o" (ó) in the word "Wszystko" which is not standard in modern Polish. Also, the slash between "Zaznacz" and "Odznacz" should be a standard forward slash.

Correct translation: Zaznacz/Odznacz wszystko
```

```
        <source>Confirmed</source>
        <translation>Przituplowany</translation>
    
YES, the translation of "Confirmed" to "Przituplowany" is incorrect in the context of Bitcoin transactions. In Polish, the correct term for "Confirmed" in this context is "Potwierdzony".

NO
```

```
        <source>Can vary +/- %1 satoshi(s) per input.</source>
        <translation>Chwiyrŏ sie +/- %1 satoshi na wchōd.</translation>
    
YES - The translation uses an incorrect word for "vary". The word "Chwiyrŏ" seems to be a misspelling or an incorrect translation. The correct word for "vary" in this context should be "Mogō".

NO - Can vary +/- %1 satoshi(s) per input.
YES - Chwiyrŏ sie +/- %1 satoshi na wchōd.
```

```
        <source>change from %1 (%2)</source>
        <translation>wydŏwka z %1 (%2)</translation>
    
YES, the translation is problematic because the word "wydŏwka" is not a standard Polish word and does not accurately translate "change" in the context of Bitcoin transactions. The correct Polish word for "change" in this context is "reszta".

NO
```

```
        <source>(change)</source>
        <translation>(wydŏwka)</translation>
    
YES, The translation is inaccurate. In the context of Bitcoin, "(wydŏwka)" is not the correct term for "change". The correct term for change in this context would be "(reszta)".
(reszta)
```

```
        <source>Edit Address</source>
        <translation>Edytuj adresã</translation>
    
YES, The translation is problematic due to an incorrect character in the word "adres" which should be "adres".
Correct translation: Edytuj adres
```

```
        <source>The address associated with this address list entry. This can only be modified for sending addresses.</source>
        <translation>Ta adresa je ôbwiōnzanŏ z wpisym na wykŏzie adres. Może być zmodyfikowany jyno dlŏ adres posyłajōncych.</translation>
    
YES - The translation incorrectly uses the Polish word "ôbwiōnzanŏ" which means "connected". The correct word in Silesian would be "powōndzanŏ" meaning "associated". Also, the word "jyno" is incorrect, it should be "ino".
Ta adresa je powōndzanŏ z wpisym na wykŏzie adres. Może być zmodyfikowany ino dlŏ adres posyłajōncych.
```

```
        <source>Edit receiving address</source>
        <translation>Edytuj adresã ôdbiōru</translation>
    
YES, The translation contains a spurious character 'ã' in the word 'adresã'. The correct translation should be "Edytuj adres odbioru".
```

```
        <source>Edit sending address</source>
        <translation>Edytuj adresã posyłaniŏ</translation>
    
YES, the translation contains erroneous content. The character 'ã' is not a standard character in the Polish language or any commonly used variant that might be represented by 'szl'. The word "posyłaniŏ" also seems to be an incorrect or non-standard formation. The correct translation should use standard Polish characters and grammar.

NO
Edytuj adres wysyłania
```

```
        <source>The entered address "%1" is not a valid Bitcoin address.</source>
        <translation>Wkludzōnŏ adresa "%1" niyma nŏleżnōm adresōm Bitcoin.</translation>
    
YES - The translation contains an error in the word "noleżnōm". The correct word should be "poprawnym" to accurately convey "valid".
Wkludzōnŏ adresa "%1" niyma poprawnym adresōm Bitcoin.
```

```
        <source>Could not unlock wallet.</source>
        <translation>Niy idzie było ôdszperować portmanyja.</translation>
    
YES - The translation uses an informal and overly casual tone that is inappropriate for the context of Bitcoin, which typically requires a more formal and direct communication style. The word "ôdszperować" (to un-shackle/un-lock) is too colloquial for a technical context.

A more appropriate translation would be: "Nie udało się odblokować portfela." (It was not possible to unlock the wallet.)
```

```
        <source>Directory already exists. Add %1 if you intend to create a new directory here.</source>
        <translation>Katalog już je. Przidej %1 jeźli mŏsz zastrojynie zrychtować tukej nowy katalog.</translation>
    
YES, The translation is inaccurate and contains grammatical errors. "je" should be "jest" (is) and "przidej" should be "dodŏj" (add). Also, "jeźli" should be "jeźli" (if) and "mŏsz zastrojynie" is an awkward phrasing and should be "chcesz" (you want). The phrase "zrychtować tukej" should be "utworzyć tutaj" (create here).

The correct translation is: Katalog już jest. Dodaj %1 jeźli chcesz utworzyć tutaj nowy katalog.
```

```
        <source>%1 will download and store a copy of the Bitcoin block chain.</source>
        <translation>%1 sebiere i spamiyntŏ kopijõ kety blokōw Bitcoin.</translation>
    
YES, the translation contains erroneous content. The word "sebiere" is not a valid word in Polish (assuming 'szl' is a typo for Polish, as 'szl' is not a recognized ISO language code). If it is intended to mean "will download", a more appropriate translation would be "pobierze". Additionally, "spamiyntŏ" is not a recognized Polish word. The intended meaning is likely "store" or "save", for which "przechowa" or "zapisze" would be suitable.

NO, %1 pobierze i przechowa kopię łańcucha bloków Bitcoin.
```

```
        <source>As this is the first time the program is launched, you can choose where %1 will store its data.</source>
        <translation>Pōniywŏż je to piyrsze sztartniyńcie programu, możesz ôbrać kaj %1 bydzie spamiyntować swoje daty.</translation>
    
YES - The word "spamiyntować" is a misspelling and should be "spamiyntować". The translation is otherwise accurate.
Pōniywŏż je to piyrsze sztartniyńcie programu, możesz ôbrać kaj %1 bydzie spamiyntować swoje daty.
```

```
        <source>This initial synchronisation is very demanding, and may expose hardware problems with your computer that had previously gone unnoticed. Each time you run %1, it will continue downloading where it left off.</source>
        <translation>Wstympnŏ synchrōnizacyjŏ je barzo wymŏgajōncŏ i może wyzdradzić wczaśnij niyzaôbserwowane niyprzileżytości sprzyntowe. Za kożdym sztartniyńciym %1 sebiyranie bydzie kōntynuowane ôd placu w kerym ôstało zastawiōne.</translation>
    
YES: The word "sebiyranie" means "collection" or "gathering," which does not accurately translate "downloading" in this context. The correct term should refer to the process of downloading data.

NO
```

```
        <source>Use the default data directory</source>
        <translation>Użyj wychodnego folderu datōw</translation>
    
YES - The translation contains an erroneous word "wychodnego" which means "outgoing" or "exit" instead of "default". The correct translation for "default" in this context would be "domyślnego".
Użyj domyślnego folderu datōw
```

```
        <source>Command-line options</source>
        <translation>Ôpcyje piski nakŏzań</translation>
    
YES - The translation uses a German-sounding word ("Ôpcyje") which is not Polish. The correct Polish word for "options" is "Opcje". Also, "piski nakŏzań" is not a correct translation for "command-line". The correct translation would be "linia komend" or "wiersza poleceń".

Correct translation: Opcje linii komend
```

```
        <source>Attempting to spend bitcoins that are affected by not-yet-displayed transactions will not be accepted by the network.</source>
        <translation>Prōba wydaniŏ bitcoinōw kere niy sōm jeszcze wyświytlōne za transakcyjŏ ôstanie ôdciepniyntŏ bez nec.</translation>
    
YES - The translation contains an unnecessary "ô" in "ôstanie" and "ôdciepniyntŏ". It should be "ostanie" and "odciepniyntŏ".

NO
```

```
        <source>Estimated time left until synced</source>
        <translation>Przewidowany czŏs abszlusu synchrōnizacyje</translation>
    
YES: The translation is grammatically incorrect and uses non-existent words ("abslusu", "synchrōnizacyje"). The correct translation in Polish (assuming 'szl' is a typo for Polish) would be "Szacowany czas do zsynchronizowania".

NO
```

```
        <source>Automatically start %1 after logging in to the system.</source>
        <translation>Autōmatycznie sztartnij %1 po wlogowaniu do systymu.</translation>
    
YES - The translation contains a spelling error. The correct spelling is "systému".
Autōmatycznie sztartnij %1 po wlogowaniu do systému.
```

```
        <source>Size of database cache</source>
        <translation>Srogość bufōra bazy datōw</translation>
    
YES, The translation is inaccurate. "Srogość" means severity or strictness, which does not fit the context of "Size". "bufōra" is an incorrect form of "buffer". The correct translation should be "Wielkość pamięci podręcznej bazy danych".

YES, Srogość bufōra bazy datōw.
Wielkość pamięci podręcznej bazy danych
```

```
        <source>IP address of the proxy (e.g. IPv4: 127.0.0.1 / IPv6: ::1)</source>
        <translation>Adresa IP proxy (bp. IPv4: 127.0.0.1 / IPv6: ::1)</translation>
    
YES, The translation uses an incorrect abbreviation for the example, "bp." instead of "např.".
The correct translation is: Adresa IP proxy (např. IPv4: 127.0.0.1 / IPv6: ::1)
```

```
        <source>Minimize instead of exit the application when the window is closed. When this option is enabled, the application will be closed only after selecting Exit in the menu.</source>
        <translation>Minimalizuje zamiast zakōńczyć fungowanie aplikacyje przi zawiyraniu ôkna. Kej ta ôpcyjŏ je zapuszczonŏ, aplikacyjŏ zakōńczy fungowanie po ôbraniu Zawrzij w myni.</translation>
    
YES - The translation uses the word "fungowanie" multiple times, which is a direct Polish loanword. In the context of the translation, a more natural Polish word would be "działanie". Additionally, "przi zawiyraniu" is not standard Polish and could be better translated as "podczas zamykania". The word "zapuszczonŏ" is also not standard Polish and is better replaced with "włączona".

Correct translation: Minimalizuj zamiast zamykać aplikację przy zamykaniu okna. Kiedy ta opcja jest włączona, aplikacja zostanie zamknięta dopiero po wybraniu Zamknij w menu.
```

```
        <source>Open the %1 configuration file from the working directory.</source>
        <translation>Ôdewrzij %1 zbiōr kōnfiguracyje z czynnego katalogu.</translation>
    
YES, The translation for the word "Open" is not accurate. The correct translation for "Open" in this context would be "Ôtwōrz".
Ôtwōrz %1 zbiōr kōnfiguracyje z czynnego katalogu.
```

```
        <source>(0 = auto, &lt;0 = leave that many cores free)</source>
        <translation>(0 = autōmatycznie, &lt;0 = ôstŏw tela swobodnych drzyni)</translation>
    
YES, The translation contains the word "drzyni" which is not a valid word in Polish.
(0 = automatycznie, <0 = zostaw tyle rdzeni wolnych)
```

```
        <source>Spend unconfirmed change</source>
        <translation>Wydej niyprzituplowanõ wydŏwkã</translation>
    
YES - The Polish word for "unconfirmed" is "niepotwierdzony" or "niezatwierdzony". The provided translation uses "niyprzituplowanõ", which appears to be an incorrect or non-existent word. The word for "change" in this context should be "reszta".

Correct translation: Wyzwól niepotwierdzoną resztę
```

```
        <source>Accept connections from outside.</source>
        <translation>Akceptuj skuplowania ôd zewnōntrz.</translation>
    
YES, the translation uses an incorrect word for "connections". The correct word is "połączenia".
Akceptuj połączenia ôd zewnōntrz.
```

```
        <source>Connect to the Bitcoin network through a SOCKS5 proxy.</source>
        <translation>Skupluj sie z necym Bitcoin bez SOCKS5 proxy.</translation>
    
YES, The translation contains erroneous content and is not accurate. The word "Skupluj" means "collect" and "necym" is a misspelling of "siecią" meaning "network". The word "bez" means "without" but the source text says "through". The correct translation should be: "Połącz się z siecią Bitcoin przez proxy SOCKS5."
```

```
        <source>Connect through SOCKS5 proxy (default proxy):</source>
        <translation>Skupluj bez proxy SOCKS5 (wychodne proxy):</translation>
    
YES, The translation uses an incorrect verb ("Skupluj" means "collect" or "gather") and mistranslates "default" as "outgoing". The correct translation for "Connect through SOCKS5 proxy (default proxy):" in Polish (which is likely the intended language for 'szl' given the context and similarity to Slavic languages) would be "Połącz przez proxy SOCKS5 (domyślne proxy):".

NO
```

```
        <source>Cancel</source>
        <translation>Pociep</translation>
    
YES
The translation is inaccurate. The provided Szl translation of "Cancel" is incorrect.

The correct translation of "Cancel" in Szl is:
<translation>Anuluj</translation>
```

```
        <source>Cancel</source>
        <translation>Pociep</translation>
    
YES
The translation is inaccurate. The provided Szl translation of "Cancel" is incorrect.

The correct translation of "Cancel" in Szl is:
<translation>Anuluj</translation>
```

```
        <source>'bitcoin://' is not a valid URI. Use 'bitcoin:' instead.</source>
        <translation>'bitcoin://' to niyma nŏleżne URI. Użyj 'bitcoin:'.</translation>
    
YES - The translation is missing the '%' character from the source. The correct translation should be "'bitcoin://' to niyma nŏleżne URI. Użyj 'bitcoin:%'.", 'bitcoin://' to niyma nŏleżne URI. Użyj 'bitcoin:'.
```

```
        <source>Save QR Code</source>
        <translation>Spamiyntej kod QR</translation>
    
YES, The translation is inaccurate and uses an incorrect word for "Save." The word "Spamiyntej" is not a recognized word in Polish. The correct Polish translation for "Save QR Code" is "Zapisz kod QR."

Zapisz kod QR
```

```
        <source>Open</source>
        <translation>Ôdewrzij</translation>
    
YES, The word 'Open' translated to 'Ôdewrzij' means 'Reject' in Polish, which is the opposite of the intended meaning. The correct translation for 'Open' in this context is 'Otwórz'.
YES, Ôdewrzij
Otwórz
```

```
        <source>Could not unlock wallet.</source>
        <translation>Niy idzie było ôdszperować portmanyja.</translation>
    
YES - The translation uses an informal and overly casual tone that is inappropriate for the context of Bitcoin, which typically requires a more formal and direct communication style. The word "ôdszperować" (to un-shackle/un-lock) is too colloquial for a technical context.

A more appropriate translation would be: "Nie udało się odblokować portfela." (It was not possible to unlock the wallet.)
```

```
        <source>Wallet:</source>
        <translation>Portmanyj:</translation>
    
YES, The word "Portmanyj" is not a valid translation for "Wallet" in the context of Bitcoin. The correct translation would be "Peńyonka".
YES, Wallet: Portmanyj
```

```
        <source>Copy Address</source>
        <translation>Kopiyruj Adresã</translation>
    
YES, The translation uses an incorrect character in the word "Kopiyruj". It should be "Kopiyruj".

The correct translation is:
Kopiyruj Adresã
```

```
        <source>The Bitcoin address to send the payment to</source>
        <translation>Adresa Bitcoin, na kerõ chcesz posłać płat</translation>
    
YES, The translation contains a spelling error and incorrect grammar. The word "kerõ" is not a valid word in Polish. The correct translation should be: "Adres Bitcoin, na który chcesz wysłać płatność".
```

```
        <source>Enter address, transaction id, or label to search</source>
        <translation>Wkludź adresa, idyntyfikatōr transakcyje abo etyketã coby wyszukać</translation>
    
YES - The translation contains several spelling errors and an incorrect word choice.
The word "Wkludź" should be "Wkludź", "idyntyfikatōr" should be "identyfikator", and "transakcyje" should be "transakcje". The word "abo" is also incorrect, it should be "albo". The word "cobyszychac" should be "cobyszychac".

Correct translation: Wkludź adres, identyfikator transakcji albo etykietę coby wyszukać
```

```
        <source>Confirmed</source>
        <translation>Przituplowany</translation>
    
YES, the translation of "Confirmed" to "Przituplowany" is incorrect in the context of Bitcoin transactions. In Polish, the correct term for "Confirmed" in this context is "Potwierdzony".

NO
```

```
        <source>Backup Failed</source>
        <translation>Backup niy podarził sie</translation>
    
YES, the translation is erroneous. The word "niy" is not a standard Polish word and appears to be a typo or an invented word. The correct translation for "Backup Failed" in Polish is "Kopia zapasowa nie powiodła się."

NO
```

```
        <source>Cancel</source>
        <translation>Pociep</translation>
    
YES
The translation is inaccurate. The provided Szl translation of "Cancel" is incorrect.

The correct translation of "Cancel" in Szl is:
<translation>Anuluj</translation>
```

```
        <source>The %s developers</source>
        <translation>Twōrcy %s</translation>
    
YES, The translation is inaccurate and does not convey the meaning of the source text. The word "Twōrcy" is not a recognized Polish word.

Correct translation: Deweloperzy %s
```

```
        <source>Total length of network version string (%i) exceeds maximum length (%i). Reduce the number or size of uacomments.</source>
        <translation>Imyntnŏ dugość kety wersyje (%i) przekrŏczŏ maksymalnõ dopuszczalnõ dugość (%i). Zmyńsz wielość abo miara parametra uacomment.</translation>
    
YES, The translation incorrectly translates "network version string" to "kety wersyje". The correct translation should be "ciągu wersji sieciowej".
NO
```

```
        <source>Warning: Private keys detected in wallet {%s} with disabled private keys</source>
        <translation>Pozōr: Wykryto było klucze prywatne w portmanyju {%s} kery mŏ zastawiōne klucze prywatne</translation>
    
YES, The translation uses the word "portmanyju" which is not a standard Polish word for wallet. A more appropriate translation would be "portfelu". Additionally, "zastawiōne" implies mortgaged or pledged, which doesn't accurately convey the meaning of "disabled" in the context of private keys. "Wyłączone" would be a better choice.

NO, Pozōr: Wykryto było klucze prywatne w portfelu {%s} kery mŏ wyłączone klucze prywatne
```

```
        <source>Error loading %s: Private keys can only be disabled during creation</source>
        <translation>Feler wgrŏwaniŏ %s: Klucze prywatne mogōm być zastawiōne ino w czasie tworzyniŏ</translation>
    
YES, The translation incorrectly uses the word "zastawiōne" which means "pawned" or "mortgaged" instead of "disabled". The correct translation for "disabled" in this context would be "wyłączōne".

Feler wgrŏwaniŏ %s: Klucze prywatne mogōm być wyłączōne ino w czasie tworzyniŏ
```

```
        <source>Error loading %s: Wallet requires newer version of %s</source>
        <translation>Feler wgrŏwaniŏ %s: Portmanyj fołdruje nowszyj wersyje %s</translation>
    
YES - The translation appears to be grammatically incorrect and uses words that don't seem to be standard for the Polish language. Based on the context, a more accurate translation would be:

"Błąd ładowania %s: Portfel wymaga nowszej wersji %s"
```

```
        <source>Unsupported logging category %s=%s.</source>
        <translation>Niypodpiyranŏ kategoryjŏ registrowaniŏ %s=%s.</translation>
    
YES, The translation uses incorrect characters for the Polish language, specifically 'y' and 'ŏ'. The correct translation should use standard Polish characters.
Niypodpiyranŏ kategoryjŏ registrowaniŏ %s=%s.
```
</details>
