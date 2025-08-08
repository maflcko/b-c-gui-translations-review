# Translations Review by LLM (✨ experimental)

The review quality depends on the LLM and the language. Currently, a fast LLM without rate limits is used. If you are interested in better quality for a specific language, please file an issue to ask for it to be re-run with a stronger model.



<details><summary>lv</summary>

[If the result is of low quality, please file an issue to find a better LLM for this language.](../../issues/new?title=%5Blv%5D%20low%20quality)


<!-- cache_translation_check_lv_7a833c311d541cf550b7d8321b3bc3c77b0f929a8e0d7dedb29ef7d3197082c7 -->
```
        <source>Enter the new passphrase for the wallet.&lt;br/&gt;Please use a passphrase of &lt;b&gt;ten or more random characters&lt;/b&gt;, or &lt;b&gt;eight or more words&lt;/b&gt;.</source>
        <translation>Ievadiet savu paroli Jūsu maciņam, lūdzu lietojiet vismaz desmit simbolus, astoņus vai vairāk vārdus.</translation>
    
ERR
The Latvian translation does not closely follow the source text's structure and misses important information:

1. The instruction of "ten or more random characters" and "eight or more words" is combined ambiguously, losing the "random" property for characters.
2. The translation omits the HTML tags (&lt;br/&gt;, &lt;b&gt;), which could affect formatting.
3. The pronoun switch ("savu" and "Jūsu") is inconsistent and unnecessary.
4. "Please use" is translated as a continuous clause rather than a separate instruction.
5. The direct connection between the requirements (symbols and words) is somewhat unclear.

Correct translation:
Ievadiet jauno maciņa paroli.&lt;br/&gt;Lūdzu, izmantojiet paroli ar &lt;b&gt;vismaz desmit nejaušiem simboliem&lt;/b&gt; vai &lt;b&gt;vismaz astoņiem vārdiem&lt;/b&gt;.
```

<!-- cache_translation_check_lv_1b01834924672c97f0df4fcd0fe12881a562ded96e5ad61aceeb1792102da369 -->
```
        <source>Port:</source>
        <translation>Ports:</translation>
    
ERR
The translation "Ports:" is incorrect because the English word "Port:" (singular) should be translated to the Latvian singular form "Ports:". However, "ports" in Latvian (meaning a network port) is indeed "ports", but without the plural "s" if it is singular, and Latvian would often keep the word "Ports:" with a capital P to match English layout.

Correct translation:
Ports:
```
</details>

Number of issues: 2.
