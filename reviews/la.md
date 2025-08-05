# Translations Review by LLM (✨ experimental)

The review quality depends on the LLM and the language. Currently, a fast LLM without rate limits is used. If you are interested in better quality for a specific language, please file an issue to ask for it to be re-run with a stronger model.



<details><summary>la</summary>

[If the result is of low quality, please file an issue to find a better LLM for this language.](../../issues/new?title=%5Bla%5D%20low%20quality)


```
        <source>Transactions</source>
        <translation>Transactiones</translation>
    
YES  
The correct Latin plural of "transaction" should be "Transactiones" (with a 't' after 'c'), but in the provided translation, it is incorrectly spelled as "Transactiones" which appears correct orthographically. However, the source shows "Transactions" and the translation is "Transactiones"—this is accurate Latin pluralization.

There is no whitespace or format specifier issue, and "Transactiones" is a reasonable Latin translation.

Therefore, the translation is unproblematic.

<reply>NO</reply>
```

```
        <source>Quit application</source>
        <translation>Exi applicatione</translation>
    
YES
The Latin word for "application" should be fully Latinized or explained, as "applicatione" is a non-classical form and "application" as a loanword should be adapted or replaced by a Latin equivalent. Also, the imperative form of "to leave" or "to quit" in Latin should be "Exi" (correct for singular "leave!"). A better translation would be:

"Exit applicationem" 

Here "applicationem" is the accusative singular form (assuming "application" is a feminine noun adapted into Latin), which fits as the direct object of "exi" (leave/quit). Alternatively, if a more classical approach is desired, "Quit application" could be "Relinque programmam" or "Desine cum programma" but given the context, "Exit applicationem" is precise and clear.
```

```
        <source>Send coins to a Bitcoin address</source>
        <translation>Mitte nummos ad inscriptionem Bitcoin</translation>
    
YES  
The Latin translation contains errors: "nummos" (coins) is correct but "inscriptionem" means "an inscription" or "a writing," which is not the usual term for "address" in the sense of a Bitcoin address. A better word for address in this technical context would be "inscriptio" (a written address or label). Also, "Mitte" is the imperative of "mitto," correct for "Send," but the accusative "nummos" should be kept. The phrase should be smoother as: "Mitte nummos ad inscriptionem Bitcoin" → "Mitte nummos ad inscriptionem Bitcoin" has a form issue; better is "Mitte nummos ad inscriptionem Bitcoin" → "Mitte nummos ad inscriptionem Bitcoin" → "Mitte nummos ad inscriptionem Bitcoin". Actually, "inscriptio" is a feminine noun of third declension, nominative singular "inscriptio," genitive "inscriptionis," accusative "inscriptionem." So "ad inscrip**tionem**" is correct. So, "Mitte nummos ad inscriptionem Bitcoin" should be "Mitte nummos ad inscriptiōnem Bitcoin," but "inscriptio" is a better word than "inscriptio" spelled without the macron. Also, "Bitcoin" is a proper noun and is better left unchanged.  

Therefore, the corrected translation is:  
"Mitte nummos ad inscriptiōnem Bitcoin"  

(Note: In LaTeX-based Latin, macrons may not be used, so "inscriptionem" is acceptable.)  

Correct translation:  
Mitte nummos ad inscriptionem Bitcoin
```

```
        <source>Change the passphrase used for wallet encryption</source>
        <translation>Muta tesseram utam pro cassidilis cifrando</translation>
    
YES  
The Latin translation contains errors and does not accurately convey the meaning of the original English text.

- "Muta tesseram" is roughly "change the password," but "tessera" in Latin typically means a token or tile, not a password or passphrase.
- "utam" is incorrect; likely an attempt at "used," which should be "usum" (accusative of "usus," meaning use) or "utuntur" (they use).
- "pro cassidilis" is problematic; "cassidilis" is not a classical Latin word related to wallet. The Latin word for wallet (a purse or money pouch) could be "loculus," "capsa," or "marsupium."
- "cifrando" is a Latinized form of the English "cipher," but the gerundive or gerund form in Latin is incorrect here.
- The phrase "used for wallet encryption" needs to be translated carefully to indicate the passphrase employed to encrypt the wallet.

A better Latin translation might be:

"Mutare tesserae usum ad marsupii encryptionem"

Or, more properly:

"Mutare tesserae ad marsupii encryptionem usum"

But "encryption" itself is modern, and in classical Latin, you would have to use "cryptationem" (from Greek 'kryptos', hidden) or "clausuram" (locking, closing) or simply "obscurationem." Since the context is technical, it’s acceptable to latinize it as "encryptionem."

A suggested improved translation:

"Mutare tesserae usum pro marsupii encryptione"

Meaning: "Change the use of the passphrase for the wallet encryption"

Full correction:

"Mutare tesserae usum pro marsupii encryptione"

Alternatively, to be more literal and correct:

"Mutare tesserae, quae ad marsupii encryptionem adhibetur"

("Change the passphrase which is used for wallet encryption")

Final recommendation:

"Mutare tesserae, quae ad marsupii encryptionem adhibetur"

Hence, the current translation is incorrect.

Correct translation:  
Mutare tesserae, quae ad marsupii encryptionem adhibetur
```

```
        <source>Send</source>
        <translation>Mitte</translation>
    
YES  
The Latin (language code 'la') word "Mitte" is not correct as it appears to be German (meaning "middle" or the imperative form of "to send"). The correct Latin translation for "Send" (imperative form) would be "Mitte" only if it were Latin, but it is not. The proper Latin imperative for "Send" (as in "send something") is "Mitte" if it's actually Latin, but "mitte" is actually the Latin imperative for the verb "mittere" (to send). However, Latin is case-sensitive and the imperative is lowercase "mitte". Also, if this is a UI label, capitalizing the first letter is common.

So, if "la" refers to Latin, then "Mitte" is appropriate as the imperative "send". Therefore, the translation is acceptable. However, the question is whether "Mitte" is correct Latin or confused with German.

Given the concerns:

- "Mitte" in German means "middle" or an imperative "send" (second person singular) of "mitten" (not common).  
- In Latin, the imperative singular of "mittere" is "mitte" (lowercase 'm').  
- Since the translation is capitalized "Mitte", it might look like German or a capitalized Latin word for a button.

In UI, capitalizing the first letter is normal even if Latin word is originally lowercase imperative.

Conclusion: The translation is appropriate for Latin imperative "Send".

No format specifiers or spacing issues exist.

<reply>NO</reply>
```

```
        <source>Encrypt the private keys that belong to your wallet</source>
        <translation>Cifra claves privatas quae cassidili tui sunt</translation>
    
YES  
The Latin translation provided is understandable but has minor issues: "cassidili" is incorrect for "wallet." The correct Latin term for "wallet" in this context would be "capsa" or "loculus," though these are approximations due to no exact classical word for a modern wallet. Also, "claves privatae" is the proper Latin word order ("private keys"). Additionally, "cifra" is a modern borrow and less classical; "encriptare" or "criptare" are also modern; using "cryptare" or the classical "obserare" or "sigillare" could be considered.

A clearer classical Latin translation would be:

"Claves privatas, quæ ad capsam tuam pertinent, cyrpta."

Or, more literally,

"Cifra claves privatas quae ad capsam tuam pertinent."

If keeping "encrypt" as "cifra," the rest should be corrected for grammar and word choice:

Corrected translation:  
"Cifra claves privatas quae ad capsam tuam pertinent"
```

```
        <source>Information</source>
        <translation>Informatio</translation>
    
YES
The Latin word for "Information" is "Informātiō" (with a long 'ā' and the correct nominative ending '-tiō'). "Informatio" lacks the correct ending and vowel length marks which are important in Latin, and is not the standard classical Latin form.

Correct translation:
Informātiō
```

```
        <source>Choose the default subdivision unit to show in the interface and when sending coins.</source>
        <translation>Selige praedefinitam unitam subdivisionis monstrare in interfacie et quando nummos mittere</translation>
    
YES  
The Latin translation has multiple issues: "Selige" is not a proper Latin word (it seems like a misspelling or incorrect form), and the sentence lacks proper grammar and word order. Also, the infinitive "monstrare" at the end is not linked well to the main verb. A better translation would use a correct imperatival or subjunctive form and clearer structure.

Correct translation:  
"Elige praedefinitam unitatem subdivisionis ut in interfacie et cum nummos mittendo ostendetur."
```

```
        <source>Cannot start bitcoin: click-to-pay handler</source>
        <translation>Bitcoin incipere non potest: cliccare-ad-pensandum handler</translation>
    
YES  
The Latin translation mixes Latin and English awkwardly. The phrase "cliccare-ad-pensandum handler" is a calque and not proper Latin. "cliccare" is not Latin but Italian-derived, and "handler" is an English word untranslated. Also, the phrase should try to remain Latin throughout.

A better Latin translation would be:  
"Bitcoin incipere non potest: gestorem click-to-pay"  
or fully Latinized as:  
"Bitcoin incipere non potest: curator click-to-pay"  

However, as "click-to-pay" is a modern technical term without a classical Latin equivalent, it may be retained in English or lightly Latinized.

Correct translation:  
Bitcoin incipere non potest: curator click-to-pay
```
</details>
