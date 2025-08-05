# Translations Review by LLM (✨ experimental)

The review quality depends on the LLM and the language. Currently, a fast LLM without rate limits is used. If you are interested in better quality for a specific language, please file an issue to ask for it to be re-run with a stronger model.



<details><summary>tn</summary>

[If the result is of low quality, please file an issue to find a better LLM for this language.](../../issues/new?title=%5Btn%5D%20low%20quality)


```
        <source>Delete the currently selected address from the list</source>
        <translation>Phimola aterese e e tlhophilweng gompieno mo lenaaneng</translation>
    
YES
The translation contains spelling and grammar issues in the 'tn' language (Tswana). Specifically:
- "Phimola" should be "Phumola" (delete/rest).
- "aterese" should be "aterese" is acceptable, but the reader might expect "aterese" as is.
- "e e tlhophilweng" is correct for "the selected."
- "gompieno" means "today" but here it is better translated as "currently" or "currently selected" with "gompieno" acceptable.
- "mo lenaaneng" has a typo; should be "mo lenaaneng" is correct for "in the list."

A more natural and grammatically correct translation is:
"Phumola aterese e e tlhophilweng gompieno mo lenaaneng"

If "Phumola" is less common for "delete," a clearer verb might be "Tlosa" (remove), so an alternative translation is:
"Tlosa aterese e e tlhophilweng gompieno mo lenaaneng"

Correct translation:
Tlosa aterese e e tlhophilweng gompieno mo lenaaneng
```

```
        <source>Copy Address</source>
        <translation>Kopitsa</translation>
    
YES  
The translation "Kopitsa" means "Copy" but does not include the word "Address," which is necessary for accuracy and clarity in the Bitcoin context. The source phrase "Copy Address" should reflect both words.  

A more accurate translation would be:  
"Kopitsa Aterese" (assuming "Aterese" is the correct word for "Address" in 'tn').
```

```
        <source>Copy Label</source>
        <translation>Kopiya le Mefuta</translation>
    
YES  
The source text "Copy Label" refers to copying a label (a tag or name), but the translation "Kopiya le Mefuta" in 'tn' language translates roughly to "Copy the Type/Kind," which is inaccurate. The word "Mefuta" means "type" or "kind," not "label."  

Correct translation in 'tn' would more accurately be:  
"Kopiya Letshwao" (where "Letshwao" means label or tag in Tswana).
```

```
        <source>There was an error trying to save the address list to %1. Please try again.</source>
        <extracomment>An error message. %1 is a stand-in argument for the name of the file we attempted to save to.</extracomment>
        <translation>Go na le phoso fa go nepa go boloka lenane la aterese go %1. Please leka gape</translation>
    
YES  
The translation mixes the local language ('tn' presumably Tswana) with English ("Please"), which is inconsistent. Also, there is a missing punctuation mark (full stop) at the end of the sentence. The phrase "fa go nepa" is awkward; a more natural phrase would be "fa go na le phoso" (there was an error). The rest of the sentence is acceptable. The format specifier %1 is correctly retained without extra spaces.

Correct translation:  
Go na le phoso fa go ne leka go boloka lenane la aterese go %1. Tsweetswee leka gape.
```

```
        <source>Exporting Failed</source>
        <translation>Phetolelo E Thutile</translation>
    
YES  
The translation is incorrect. "Phetolelo E Thutile" literally translates to "Translation is finished" instead of "Exporting Failed." The correct translation for "Exporting Failed" in Tswana (tn) should convey failure in the exporting process. A better translation would be:

"Phetolelo e Hlōlehile"
```

```
        <source>Enter passphrase</source>
        <translation>Tsenya faele ya go tsena</translation>
    
YES  
The translation is inaccurate. "Enter passphrase" should be translated as a phrase instructing the user to input their passphrase. The provided translation "Tsenya faele ya go tsena" means "Enter the file to enter," which is incorrect and unrelated. 

A correct translation in Tswana (tn) would be:  
"Tsenya lefoko la phatlalatso"  
(or simply "Tsenya lefoko la sephiri," meaning "Enter the secret word/passphrase.")
```

```
        <source>New passphrase</source>
        <translation>Fase ya go bidiwa e ntšha</translation>
    
UNK_LANG, not familiar with the Tswana language 'tn'.
```

```
        <source>Encrypt wallet</source>
        <translation>Tsamaisa phokotso</translation>
    
YES  
The translation "Tsamaisa phokotso" does not accurately convey "Encrypt wallet." In the context of Bitcoin, "Encrypt wallet" means to secure the wallet data via encryption, not "manage" or "drive" any kind of reduction ("phokotso" means reduction/decrease in some Southern African languages like Sesotho or Setswana).  

A more accurate translation in 'tn' (likely referring to Setswana) would be:  
"Fihlela mokotla wa ditšhelete" or "Sireletsa mokotla wa ditšhelete ka phokotso" (where "phokotso" means encryption is tricky, as Setswana might use a borrowed or descriptive phrase).  

A suitable clear translation would be:  
"Enkripita mokotla wa ditšhelete" (using a borrowed form "Enkripita" for encrypt)  
or  
"Tsireletsa mokotla wa ditšhelete ka mokhoa wa go phokotsa tshedimosetso" (Protect wallet by reducing data – a descriptive but cumbersome phrase).  

Given the complexity and standard usage, the best practical corrected translation is:  
"Enkripita mokotla wa ditšhelete"  

Correct translation:  
<translation>Enkripita mokotla wa ditšhelete</translation>
```

```
        <source>This operation needs your wallet passphrase to unlock the wallet.</source>
        <translation>Tiro e e tlhoka polelo ya faele ya pokello ya gago go bula pokello.</translation>
    
YES  
The translation has some issues with word choice and clarity in the 'tn' (Tswana) language. The English phrase "wallet passphrase" is translated as "polelo ya faele ya pokello," which literally means "file phrase of the collection," which is incorrect and confusing.

A more accurate translation would clearly refer to a "passphrase" (password or secret phrase) used to unlock the "wallet" (pokello). The phrase "wallet passphrase" could be translated as "polelo ya sephiri ya pokello ya gago" (your wallet's secret phrase).

Correct translation:  
Tiro e e tlhoka polelo ya sephiri ya pokello ya gago go bula pokello.
```

```
        <source>Unlock wallet</source>
        <translation>Tshwaola pocket</translation>
    
YES
The translation is problematic. The English phrase "Unlock wallet" means to remove the lock or security from a Bitcoin wallet. The provided translation "Tshwaola pocket" uses "pocket" which is an English word and unrelated to the correct term for "wallet" in Tswana (language code 'tn'). The verb "Tshwaola" seems to aim to mean "unlock," but it is not accurate or standard.

Correct translation:
"Ntsha wallet" or more properly "Bulela pokello" (where "pokello" means collection or wallet, and "bulela" means open/unlock).
However, common usage often borrows "wallet" as "walete" or uses "pokello" for wallet.

A concise and accurate translation could be:
"Bulela pokello"
```

```
        <source>Enter the new passphrase for the wallet.&lt;br/&gt;Please use a passphrase of &lt;b&gt;ten or more random characters&lt;/b&gt;, or &lt;b&gt;eight or more words&lt;/b&gt;.</source>
        <translation>Tsamaya ka polelo e ncha ya pasefese ya walle.&lt;br/&gt;Tlh please dirisa polelo ya go fetola ya &lt;b&gt;dintlha tse lesome kgotsa tse fetang tseo di sa ikanyegang&lt;/b&gt;, goba &lt;b&gt;Dikgang tse robong kgotsa go feta&lt;/b&gt;.</translation>
    
YES  
The translation contains a mix of languages and some incorrect or unclear terms. For example, "Tsamaya ka polelo e ncha ya pasefese ya walle" is awkward and partially not in 'tn' (Tswana). The English word "please" is used directly as "Tlh please", which is inappropriate. The phrase "polelo ya go fetola" (phrase of changing) does not accurately translate "passphrase." Also, "Dikgang tse robong" means "news/stories of nine," which is incorrect in this context; it should refer to "words."

Correct translation:  
"Tsena phasefose e ntšha ya pokello.&lt;br/&gt;Tsweetswee dirisa phasefose ya &lt;b&gt;ditlhaka tse lesome kgotsa tse fetang tse sa ikanyegang&lt;/b&gt;, kgotsa &lt;b&gt;mantšu a le robedi kgotsa a fetang ao&lt;/b&gt;."
```

```
        <source>Enter the old passphrase and new passphrase for the wallet.</source>
        <translation>Tshupisa setlhogo sa kgale le setlhogo se se ntšha sa phasphore ya wallet.</translation>
    
YES
The translation contains several errors and awkward phrasing. The word "Tshupisa" is not appropriate for "Enter" in this context; a better verb would be "Kenya" or "Tlatsa" for entering data. The phrase "setlhogo" literally means "head," which is incorrect for "passphrase." The correct term should be "phasesefala" or a phrase meaning "password/passphrase." Also, "phasphore" does not correspond to a correct word in Setswana, and mixing English "wallet" untranslated is acceptable only if no suitable equivalent exists, but "wallet" can be translated as "mokotlana" or left untranslated consistently. The structure should be clearer and more natural.

Correct translation:
Kenya phasesefala e kgale le phasesefala e ntšha ya mokotlana.
```

```
        <source>Wallet to be encrypted</source>
        <translation>Puso e tla fetolelwa ka netefatso</translation>
    
UNK_LANG, not familiar with the Tswana language 'tn'.
```

```
        <source>Your wallet is about to be encrypted. </source>
        <translation>Puso ya gago e tla simolola go naya boloko.</translation>
    
UNK_LANG, not familiar with the Tswana language 'tn'.
```

```
        <source>Your wallet is now encrypted. </source>
        <translation>Pasepoto ya gago jaanong e kopilwe.</translation>
    
YES  
The translation uses "Pasepoto ya gago jaanong e kopilwe." which translates roughly as "Your passport is now copied," which is incorrect for the intended meaning of "Your wallet is now encrypted."  
A correct translation in Tswana ('tn') should refer to the wallet ("pokete" or "wallet") and encryption ("go di dira sephiri" or "go di bolela ka tshireletsego").  

Correct translation:  
"Pokete ya gago jaanong e tshwanetse ka sephiri."  
or  
"Poka ya gago jaanong e dirilwe ka sephiri."
```

```
        <source>Exporting Failed</source>
        <translation>Phetolelo E Thutile</translation>
    
YES  
The translation is incorrect. "Phetolelo E Thutile" literally translates to "Translation is finished" instead of "Exporting Failed." The correct translation for "Exporting Failed" in Tswana (tn) should convey failure in the exporting process. A better translation would be:

"Phetolelo e Hlōlehile"
```
</details>
