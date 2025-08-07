# Translations Review by LLM (✨ experimental)

The review quality depends on the LLM and the language. Currently, a fast LLM without rate limits is used. If you are interested in better quality for a specific language, please file an issue to ask for it to be re-run with a stronger model.



<details><summary>tn</summary>

[If the result is of low quality, please file an issue to find a better LLM for this language.](../../issues/new?title=%5Btn%5D%20low%20quality)


```
        <source>Copy Address</source>
        <translation>Kopitsa</translation>
    
YES
The translation "Kopitsa" means "Copy" in Tswana, but it omits "Address" from the original source. This reduces clarity, especially in a Bitcoin context where address is a key term.

Correct translation:
Kopitsa aterese
```

```
        <source>Copy Label</source>
        <translation>Kopiya le Mefuta</translation>
    
YES
The translation is incorrect. "Kopiya le Mefuta" literally means "Copy and Types" or "Copy with Types" in Setswana, and "Mefuta" means "types" or "kinds", not "label". The correct word for "label" in Setswana is usually "lebole" or "setshwantsho".

Correct translation:
Kopisa Lebole
```

```
        <source>There was an error trying to save the address list to %1. Please try again.</source>
        <extracomment>An error message. %1 is a stand-in argument for the name of the file we attempted to save to.</extracomment>
        <translation>Go na le phoso fa go nepa go boloka lenane la aterese go %1. Please leka gape</translation>
    
YES
The translation is inaccurate and contains an English sentence fragment ("Please leka gape"). Also, the word order and phrasing in Setswana ('tn') is awkward and not fully grammatical.

Correct translation:
Go diragetse phoso fa go bolokiwa lenane la diaterese go %1. Ka kopo leka gape.
```

```
        <source>Exporting Failed</source>
        <translation>Phetolelo E Thutile</translation>
    
YES
The translation "Phetolelo E Thutile" means "Translation Failed" in Setswana, not "Exporting Failed." The word "Exporting" should be properly translated.

Correct translation:
Go Romela Gonne Go Itse Go Paletswe
```

```
        <source>Enter passphrase</source>
        <translation>Tsenya faele ya go tsena</translation>
    
YES
The translation is incorrect. The source text "Enter passphrase" should be translated as "Tsenya lefoko la bohlokoa" in Setswana ('tn'). The provided translation means "Enter the file to enter", which is erroneous.

Correct translation:
Tsenya lefoko la bohlokoa
```

```
        <source>New passphrase</source>
        <translation>Fase ya go bidiwa e ntšha</translation>
    
YES
The translation is inaccurate. The phrase "Fase ya go bidiwa e ntšha" means "New requested phase" or "New phase to be called," which is not the correct translation for "New passphrase." The term "passphrase" should be directly translated as "setlhopha sa lefoko la sephiri" or similar, to reflect a password.

Correct translation:
Lefoko la sephiri le lešha
```

```
        <source>Encrypt wallet</source>
        <translation>Tsamaisa phokotso</translation>
    
YES
The translation "Tsamaisa phokotso" is incorrect and misleading. It means "manage reduction" or "run reduction", which does not convey "Encrypt wallet". The correct translation into Setswana ("tn") should be along the lines of "Tshemosa walete" or "Sireletsa walete ka lefokotsipi", with "walete" being a commonly loaned word for "wallet" and "sireletsa" meaning "to protect/encrypt".

Correct translation:
Sireletsa walete ka lefokotsipi
```

```
        <source>Unlock wallet</source>
        <translation>Tshwaola pocket</translation>
    
YES
The translation is somewhat inaccurate. "Tshwaola" means "open" in Setswana ('tn'), and "pocket" is likely a direct anglicism rather than the correct word for "wallet." The more suitable word for "wallet" in Setswana is "setlwana" or "walleti." Additionally, "Unlock" in this context would be better translated as "Bulela" (open/unlock) or "Bulela walleti/setlwana."

Correct translation:
Bulela walleti
```

```
        <source>Enter the new passphrase for the wallet.&lt;br/&gt;Please use a passphrase of &lt;b&gt;ten or more random characters&lt;/b&gt;, or &lt;b&gt;eight or more words&lt;/b&gt;.</source>
        <translation>Tsamaya ka polelo e ncha ya pasefese ya walle.&lt;br/&gt;Tlh please dirisa polelo ya go fetola ya &lt;b&gt;dintlha tse lesome kgotsa tse fetang tseo di sa ikanyegang&lt;/b&gt;, goba &lt;b&gt;Dikgang tse robong kgotsa go feta&lt;/b&gt;.</translation>
    
YES
There are multiple issues:
- The translation has unnecessary direct borrowing and incorrectly localized terms (e.g., "pasefese ya walle" should be "senotlolo sa sephiri sa walete").
- The phrase "Tlh please dirisa" is incorrect; "Tlh" is not needed.
- "ya go fetola" does not mean "random".
- The translation of format specifiers (like &lt;br/&gt;, &lt;b&gt;) is fine, but capitalization for "Dikgang" is inconsistent.
- The reliability and accuracy of phrases is not maintained; e.g., "dintlha tse lesome kgotsa tse fetang tseo di sa ikanyegang" is awkward and not idiomatic.
- There are some extra spaces and slight whitespace problems within tags.

Correct translation:
Kenya senotlolo sa sephiri se sesha sa walete.&lt;br/&gt;Tsweetswee dirisa senotlolo sa sephiri se nang le &lt;b&gt;ditlhaka tse lesome kgotsa go feta tse sa tlholeng di iteriwa&lt;/b&gt;, kgotsa &lt;b&gt;mafoko a a robedi kgotsa go feta&lt;/b&gt;.
```

```
        <source>Enter the old passphrase and new passphrase for the wallet.</source>
        <translation>Tshupisa setlhogo sa kgale le setlhogo se se ntšha sa phasphore ya wallet.</translation>
    
YES
The translation incorrectly translates "passphrase" as "setlhogo", which actually means "title" or "heading" in Setswana (tn). Also, "phasphore" seems to be a misspelling, possibly an attempt to transliterate "passphrase," but using both "setlhogo" and "phasphore" adds confusion.

Correct translation:
Tsenya lefoko la sephiri la kgale le lefoko la sephiri le lesha la wallet.
```

```
        <source>Wallet to be encrypted</source>
        <translation>Puso e tla fetolelwa ka netefatso</translation>
    
YES
The translation is inaccurate. The source text "Wallet to be encrypted" refers to the wallet undergoing encryption. The translation "Puso e tla fetolelwa ka netefatso" is problematic:
- "Puso" means "government" in Setswana, not "wallet".
- "E tla fetolelwa ka netefatso" roughly means "will be changed with confirmation", which is not equivalent to "to be encrypted".

Correct translation:
Wallet e tla tsiboganngwa kgotsa serololo se tla sirelediwa
```

```
        <source>Your wallet is about to be encrypted. </source>
        <translation>Puso ya gago e tla simolola go naya boloko.</translation>
    
YES
The translation is incorrect. The English source says "Your wallet is about to be encrypted." The translation "Puso ya gago e tla simolola go naya boloko." means "Your heart is about to start giving (or receiving) protection", which is not accurate and uses "puso" (heart) instead of "wallet". It also does not convey the concept of encryption; "boloko" could mean "protection" or "salvation" but is not specific.

Correct translation:
Wallet ya gago e tlile go somisiwa/encryptiwa. 

Alternatively (using "go sireletsegileng" for "encrypted"):
Wallet ya gago e tlile go sireletsegwa ka sephiri.
```

```
        <source>Your wallet is now encrypted. </source>
        <translation>Pasepoto ya gago jaanong e kopilwe.</translation>
    
YES
The translation is problematic. "Pasepoto ya gago jaanong e kopilwe" means "Your passport is now copied." The word "pasepoto" is "passport", not "wallet", and "kopilwe" is "copied", not "encrypted".

Correct translation:
"Wallet" in Setswana is commonly "paka ya madi" or "wallet" transliterated, and "encrypted" could be "e sireleditswe" (protected/secured) or "e kentse sephiri" (has a secret). 

A more accurate translation:
"Wallet ya gago jaanong e sireleditswe."

Or more literally:
"Sepache sa gago jaanong se sireleditswe."
```

```
        <source>Exporting Failed</source>
        <translation>Phetolelo E Thutile</translation>
    
YES
The translation "Phetolelo E Thutile" means "Translation Failed" in Setswana, not "Exporting Failed." The word "Exporting" should be properly translated.

Correct translation:
Go Romela Gonne Go Itse Go Paletswe
```
</details>

Number of issues: 14.
