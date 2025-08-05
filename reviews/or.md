# Translations Review by LLM (✨ experimental)

The review quality depends on the LLM and the language. Currently, a fast LLM without rate limits is used. If you are interested in better quality for a specific language, please file an issue to ask for it to be re-run with a stronger model.



<details><summary>or</summary>

[If the result is of low quality, please file an issue to find a better LLM for this language.](../../issues/new?title=%5Bor%5D%20low%20quality)


```
        <source>There was an error trying to save the address list to %1. Please try again.</source>
        <extracomment>An error message. %1 is a stand-in argument for the name of the file we attempted to save to.</extracomment>
        <translation>ଠିକଣା ତାଲିକାକୁ ସଞ୍ଚୟ କରିବା ସମୟରେ ଏକ ତ୍ରୁଟି ହୋଇଛି%1. ଦୟାକରି ପୁନଃଚେଷ୍ଟା କରନ୍ତୁ</translation>
    
YES
There is a formatting issue: in the translation, there is no space before the placeholder %1, which should be preceded by a space to match natural spacing in the sentence. Also, the translated text misses a proper punctuation mark at the end (e.g., a period or a full stop).

Correct translation:
ଠିକଣା ତାଲିକାକୁ ସଞ୍ଚୟ କରିବା ସମୟରେ ଏକ ତ୍ରୁଟି ହୋଇଛି %1। ଦୟାକରି ପୁନଃଚେଷ୍ଟା କରନ୍ତୁ।
```

```
        <source>Warning: If you encrypt your wallet and lose your passphrase, you will &lt;b&gt;LOSE ALL OF YOUR BITCOINS&lt;/b&gt;!</source>
        <translation>ଚେତାବନୀ: ଯଦି ତୁମେ ତୁମର ୱାଲେଟକୁ ଏନକ୍ରିପ୍ଟ କର ଏବଂ ତୁମର ପାସଫ୍ରେଜ୍ ହରାଇବ, ତୁମେ କରିବ &lt;b&gt;ଆପଣଙ୍କର ସମସ୍ତ ବିଟକଏନ୍ ହରାନ୍ତୁ&lt;/b&gt;!</translation>
    
YES  
The translation has a contextual and grammatical issue. The phrase "you will &lt;b&gt;LOSE ALL OF YOUR BITCOINS&lt;/b&gt;!" should be addressed directly in the second person ("you will lose all your bitcoins"), but the translation mixes second person "ତୁମେ" (you) with a polite or third-person pronoun "ଆପଣଙ୍କର" (your, formal), causing inconsistency. Also, "କରିବ" (will do) is awkwardly placed and unnecessary here.

A more accurate and natural translation in Odia would be:

ଚେତାବନୀ: ଯଦି ତୁମେ ତୁମର ୱାଲେଟକୁ ଏନକ୍ରିପ୍ଟ କରି ପାସଫ୍ରେଜ୍ ହରାଇ ଦିଅ, ତେବେ &lt;b&gt;ତୁମର ସମସ୍ତ ବିଟକଏନ୍ ହରାଯିବ&lt;/b&gt;!

This preserves the warning tone, maintains second person throughout, and properly conveys the meaning.
```
</details>
