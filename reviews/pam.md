# Translations Review by LLM (✨ experimental)

The review quality depends on the LLM and the language. Currently, a fast LLM without rate limits is used. If you are interested in better quality for a specific language, please file an issue to ask for it to be re-run with a stronger model.



<details><summary>pam</summary>

[If the result is of low quality, please file an issue to find a better LLM for this language.](../../issues/new?title=%5Bpam%5D%20low%20quality)


```
        <source>Export</source>
        <translation>IExport</translation>
    
YES
The translation incorrectly includes an extra "I" at the beginning ("IExport"), which is not correct in Kapampangan ('pam'). The word "Export" is commonly borrowed as-is or can be rendered as "Iluwal" (to bring out/export).

Correct translation:
Iluwal
```

```
        <source>Wallet unlock failed</source>
        <translation>Memali ya ing pamag-unlock king wallet </translation>
    
YES
There is an issue with the translation:
1. The word "Memali ya ing" translates more as "It failed the ..." but the phrasing is awkward in Kapampangan ('pam') and adds unnecessary words.
2. There is an extra space before the closing tag.
3. The most natural translation for "Wallet unlock failed" would be "E megumpisa ing pamag-unlock king wallet" or simply "E me-unlock ing wallet", meaning "Wallet failed to unlock" or "Wallet was not unlocked."

Correct translation:
E me-unlock ing wallet
```

```
        <source>Wallet passphrase was successfully changed.</source>
        <translation>Mi-alilan ne ing passphrase na ning wallet.</translation>
    
YES
The translation has accuracy issues.

Explanation:
The phrase "Mi-alilan ne ing passphrase na ning wallet." awkwardly renders "was successfully changed" as "Mi-alilan ne", which is not idiomatic in Kapampangan. "Mi-alilan" means "to change", but it does not include the sense of success. The standard and more precise wording should use "me-salikut" or "me-bayu" for "was changed", but to express "successfully changed", "me-salikut yang makatuking pamagobra" or simply "me-salikut ya" could be more natural.

Correct translation:
Me-salikut ya ing passphrase ning wallet.
```

```
        <source>Last received block was generated %1 ago.</source>
        <translation>Ing tatauling block a metanggap,  me-generate ya %1 ing milabas</translation>
    
YES
The translation has both grammatical issues and the format specifier "%1" is not well integrated. "Ing tatauling block a metanggap" is awkward, and the phrase "me-generate ya %1 ing milabas" is not idiomatic in Kapampangan ('pam'). There is also a spacing issue in "block a metanggap,  me-generate" (double space after the comma).

Correct translation:
Ing pekarulang block a receive, me-generate ya %1 a milabas.
```

```
        <source>Up to date</source>
        <translation>Makatuki ya king aldo</translation>
    
YES
The translation "Makatuki ya king aldo" is problematic. "Makatuki" isn't a recognized word in Kapampangan, and "ya king aldo" translates to "today" or "for the day". The phrase "Up to date" in the context of Bitcoin software should convey "latest" or "current", referring to being synchronized with the latest blockchain state.

Correct translation:
Agpang king bayung datos

This means "[It is] according to the latest data", which properly captures "Up to date."
```

```
        <source>Edit receiving address</source>
        <translation>Alilan ya ing address king pamagpadala</translation>
    
YES
The translation is problematic. "Edit receiving address" refers to editing the address where funds are received, not sent. The translation says "address for sending" ("king pamagpadala"), which is the opposite of what is intended. Also, "alilan" for "edit" is acceptable in some contexts, but "alisan" or "ayusan" may be better for "edit" in Kapampangan (pam).

Correct translation:
Ayusan ya ing address para king pamagpasali

Alternative:
Alilan ya ing address para king pamagpasali

("pamagpasali" means "receiving.")
```

```
        <source>New key generation failed.</source>
        <translation>Memali ya ing pamangaua king key</translation>
    
YES
The translation "Memali ya ing pamangaua king key" is inaccurate and awkward. It translates literally to "Failed is the making of key," but in Kapampangan ('pam'), it is more natural and clear to say "Mealbung mag-generate key" or "E meging matagumpe ing pamag-generate ning key." Furthermore, the structure could be improved for clarity.

Correct translation:
"E meging matagumpe ing pamag-generate ning key."
or 
"Mealbung mag-generate key."
```

```
        <source>version</source>
        <translation>bersion</translation>
    
YES
The translation is incorrect. "Bersion" is a misspelling and not the correct Kapampangan ('pam') translation of "version". In Kapampangan, "version" is typically borrowed directly as "bersyun". 

Correct translation:
bersyun
```

```
        <source>The supplied proxy address is invalid.</source>
        <translation>Ing milageng proxy address eya katanggap-tanggap.</translation>
    
YES
The translation is inaccurate. "Eya katanggap-tanggap" means "is acceptable," which is the opposite of "is invalid." Additionally, "milageng" is not appropriate; "pilan" or "ibinigay" could be used for "supplied".

Correct translation:
Ing ibinigay a proxy address alayan tamu makasaup. (But this may be a poor translation as well.)

A better and direct translation would be:
Ing ibinigay a proxy address alang bisa.
```

```
        <source>Clear All</source>
        <translation>I-Clear Eganagana</translation>
    
YES
The translation "I-Clear Eganagana" is problematic. "Eganagana" does not appear to be a word in Kapampangan (pam), and "I-Clear" is an English borrowing with an unnecessary "I-". A better Kapampangan translation would use native or more commonly understood terms. "Clear" in this context likely means "limpia" (clean) or "alisan" (remove).

Correct translation:
Alisan Damu
or
I-limpia ngan

(Note: Kapampangan often borrows from Tagalog or Spanish, but "I-Clear Eganagana" is not natural or accurate. "Damu" means "all" in Kapampangan.)
```

```
        <source>Clear All</source>
        <translation>I-Clear Eganagana</translation>
    
YES
The translation "I-Clear Eganagana" is problematic. "Eganagana" does not appear to be a word in Kapampangan (pam), and "I-Clear" is an English borrowing with an unnecessary "I-". A better Kapampangan translation would use native or more commonly understood terms. "Clear" in this context likely means "limpia" (clean) or "alisan" (remove).

Correct translation:
Alisan Damu
or
I-limpia ngan

(Note: Kapampangan often borrows from Tagalog or Spanish, but "I-Clear Eganagana" is not natural or accurate. "Damu" means "all" in Kapampangan.)
```

```
        <source>not accepted</source>
        <translation>ali metanggap</translation>
    
YES
The translation "ali metanggap" is problematic and incorrect. In Kapampangan (pam), "not accepted" should be "e tanggap" or "ali tanggap". The use of "metanggap" is conjugated incorrectly.

Correct translation:
e tanggap
```

```
        <source>Transaction ID</source>
        <translation>ID</translation>
    
YES
The translation is incomplete. "ID" only reflects the "ID" part but omits "Transaction". It should provide the full phrase in 'pam' (Pampangan/Kapampangan).

Correct translation:
Transaction ID
```

```
        <source>false</source>
        <translation>e tutu</translation>
    
YES
The translation of "false" as "e tutu" is incorrect. "False" in Pampangan can be translated as "alilan" or "e totoo" (lit. "not true"), but "e tutu" is closer to "not true" in colloquial speech. While it is technically a possible rendering, for an interface context like a Bitcoin application, "alilan" or "e totoo" would be more appropriate to avoid ambiguity.

Correct translation:
alilan
or
e totoo
```

```
        <source>Export</source>
        <translation>IExport</translation>
    
YES
The translation incorrectly includes an extra "I" at the beginning ("IExport"), which is not correct in Kapampangan ('pam'). The word "Export" is commonly borrowed as-is or can be rendered as "Iluwal" (to bring out/export).

Correct translation:
Iluwal
```
</details>

Number of issues: 15.
