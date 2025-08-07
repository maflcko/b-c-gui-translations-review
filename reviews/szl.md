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
    
SPAM
The translation contains unrelated Rust code and Polish text, rather than a Silesian ('szl') translation for the given English source.

Correct translation:
Prawy klik, coby edytować adres albo etyketa
```

```
        <source>Banned Until</source>
        <translation>Szpera do</translation>
    
YES
The translation is problematic. "Szpera do" does not accurately reflect the meaning of "Banned Until" in Silesian ('szl'). "Szpera" likely comes from Polish "szperać" (to rummage), which is incorrect in this context. The correct Silesian translation should be closer to "Zablokowany do" or "Zabanowany do" (following Polish/Silesian conventions).

Correct translation:
Zabanowany do
```

```
        <source>Connect to the Bitcoin network through a SOCKS5 proxy.</source>
        <translation>Skupluj sie z necym Bitcoin bez SOCKS5 proxy.</translation>
    
YES
The translation has an error. "Skupluj sie z necym Bitcoin bez SOCKS5 proxy." translates to "Connect to the Bitcoin network without SOCKS5 proxy." The word "bez" means "without" in Silesian (szl) and Polish, which is the opposite of the source.

Correct translation:
Połącz się z necym Bitcoin przez SOCKS5 proxy.
```

```
        <source>Connect through SOCKS5 proxy (default proxy):</source>
        <translation>Skupluj bez proxy SOCKS5 (wychodne proxy):</translation>
    
YES
The translation is incorrect. The English text says "Connect through SOCKS5 proxy (default proxy):", but the 'szl' translation means "Connect without SOCKS5 proxy (outgoing proxy):", which is the opposite of the intended meaning.

Correct translation:
Połącz sie przepos proxy SOCKS5 (domyślne proxy):
```

```
        <source>The Bitcoin address to send the payment to</source>
        <translation>Adresa Bitcoin, na kerõ chcesz posłać płat</translation>
    
YES
There are a few issues:
1. The word "adresa" should be "adres" in Silesian.
2. "kerõ" is not standard Silesian; it seems to be a misspelling or dialectal, and its placement is awkward.
3. "płat" is incomplete for "payment"; "płatność" would be better, or another Silesian/Silesianized equivalent.
4. The word order doesn't clearly express "to send the payment to".

Correct translation:
Adres Bitcoin, na który chcesz posłać płatność
```
</details>

Number of issues: 5.
