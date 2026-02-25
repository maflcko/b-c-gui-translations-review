# Translations Review by LLM (✨ experimental)

The review quality depends on the LLM and the language. To report LLM shortcomings for a specific language, please file an issue. It may be possible to re-run with a stronger model. Check the git metadata of this file for the creation date.



<details><summary>lv</summary>

[If the result is outdated or of low quality, please file an issue to request and updated run for this language.](../../../issues/new?title=%5Blv%5D%20request)


<!-- cache_translation_check_lv_3f634949154e64ee8def4d7c8016908e3e729391950333f58e52424b58ac7c63 -->
```
        <source>C&amp;hoose</source>
        <translation>Izvēlēties</translation>
    
ERR
The translation omits the '&' accelerator key, which should appear exactly once to reflect the shortcut key, as in the source. In Latvian, it can be placed at a relevant position in the word.

Correct translation:
Izv&euml;lēties
```

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

<!-- cache_translation_check_lv_3136e8b64d390aef2ee79332660eb51e756bff61699bbe6a380c3d6e68c83e4a -->
```
        <source>&amp;Window</source>
        <translation>&amp;Logs</translation>
    
ERR
The translation for '&amp;Window' in Latvian should be '&amp;Logs', which is correct, but the word should be 'Logs' without adding an extra 's' (since 'logs' is singular nominative in Latvian). Also, '&amp;' is present exactly once and properly placed. However, the correct translation should be:

Correct translation:
&Logs
```

<!-- cache_translation_check_lv_884f4c5457be85b72895dc35227d98c948096f2ec3b4e87ccc233fa30c95b6c6 -->
```
        <source>&amp;Reset Options</source>
        <translation>&amp;Atiestatīt Iestatījumus.</translation>
    
ERR
There is an unnecessary period at the end of the translation ("Iestatījumus."). In user interface contexts, such buttons should not have a period at the end in Latvian, matching the English source.

Correct translation:
&Atiestatīt iestatījumus
```

<!-- cache_translation_check_lv_3136e8b64d390aef2ee79332660eb51e756bff61699bbe6a380c3d6e68c83e4a -->
```
        <source>&amp;Window</source>
        <translation>&amp;Logs</translation>
    
ERR
The translation for '&amp;Window' in Latvian should be '&amp;Logs', which is correct, but the word should be 'Logs' without adding an extra 's' (since 'logs' is singular nominative in Latvian). Also, '&amp;' is present exactly once and properly placed. However, the correct translation should be:

Correct translation:
&Logs
```

<!-- cache_translation_check_lv_04638809e4e3e472f920483ef4a98d3a28e4a1da76d33fbf1577e82985614f90 -->
```
        <source>User Interface &amp;language:</source>
        <translation>Lietotāja interfeiss un &amp;valoda:</translation>
    
ERR
The translation misinterprets the '&' in the source. In the English source, "&language" indicates the shortcut key for "language," so the ampersand should be placed before the appropriate letter of the Latvian word for "valoda." Also, "un" ("and") is not present in the English source and should not be added.

Correct translation:
Lietotāja &amp;valoda:
```
</details>

Number of issues: 6.
