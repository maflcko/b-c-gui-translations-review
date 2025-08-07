# Translations Review by LLM (✨ experimental)

The review quality depends on the LLM and the language. Currently, a fast LLM without rate limits is used. If you are interested in better quality for a specific language, please file an issue to ask for it to be re-run with a stronger model.



<details><summary>sw</summary>

[If the result is of low quality, please file an issue to find a better LLM for this language.](../../issues/new?title=%5Bsw%5D%20low%20quality)


```
        <source>Copy Label</source>
        <translation>Nakili  Chapa</translation>
    
YES
There is an extra space between "Nakili" and "Chapa" that should not exist. The correct translation should not have double spacing.

Correct translation:
Nakili Chapa
```

```
        <source>Edit</source>
        <translation> hariri</translation>
    
YES
There is a leading space before "hariri", which is unnecessary and causes a whitespace formatting issue. The correct translation should not have the leading space.

Correct translation:
<translation>Hariri</translation>
```

```
        <source>Encrypt wallet</source>
        <translation>Simba mkoba</translation>
    
YES
The translation "Simba mkoba" is problematic. In Swahili, "Simba" means "lion" and is not related to "encrypt." The correct translation for "Encrypt wallet" would be "Sificha mkoba," "Kodisha mkoba," or more accurately "Ficha mkoba" (hide wallet), but the technical term "Encryption" is best translated as "sificha" or "kodisha".

Correct translation:
Sificha mkoba
```

```
        <source>Settings file %1 might be corrupt or invalid.</source>
        <translation>Faili ya mipangilio ya asilimia %1 inaweza kuwa mbovu au batili.</translation>
    
YES
The translation incorrectly translates "%1" as "asilimia %1" which means "percent %1" in Swahili. "%1" is a format specifier and should be retained as is. The rest of the translation is otherwise accurate, but this error renders it problematic.

Correct translation:
Faili ya mipangilio %1 inaweza kuwa mbovu au batili.
```

```
        <source>Runaway exception</source>
        <translation>Ubaguzi wa kukimbia</translation>
    
YES
The translation is inaccurate. "Runaway exception" (a technical term referring to an unhandled or uncontrolled exception in programming or system execution) is translated as "Ubaguzi wa kukimbia", which means "discrimination of running" or "running discrimination", and does not convey the intended technical meaning.

Correct translation:
Hitilafu isiyoweza kudhibitiwa

Alternative acceptable translation:
Hitilafu isiyodhibitiwa
```

```
        <source>Command-line options</source>
        <translation>Chaguo za amri ya amri</translation>
    
YES
The translation is partially repetitive and a bit awkward. "Chaguo za amri ya amri" translates to "Options of command of command", which is redundant. The correct translation should be:

Chaguo za mstari wa amri

So the correct translation is:
Chaguo za mstari wa amri
```

```
        <source>Hide</source>
        <translation>Ficha</translation>
    
YES
The translation "Ficha" in Swahili is incorrect for "Hide". The correct Swahili translation is "Ficha" for the verb "to hide", so contextually it could be correct, but "Hide" as a command (like a button) would better be translated as "Ficha" as well. However, since "Ficha" is already correct for Swahili "Hide", there is no problem.

NO
```

```
        <source>Show</source>
        <translation>Jinsi  jinsi</translation>
    
YES
The translation is incorrect. "Jinsi jinsi" does not correspond to "Show" in Swahili. The correct translation should be "Onyesha".

Correct translation:
Onyesha
```

```
        <source>Error</source>
        <translation>Onyo</translation>
    
YES
The translation of "Error" as "Onyo" is incorrect. "Onyo" means "Warning" in Swahili.

Correct translation:
Hitilafu
```

```
        <source>Error</source>
        <translation>Onyo</translation>
    
YES
The translation of "Error" as "Onyo" is incorrect. "Onyo" means "Warning" in Swahili.

Correct translation:
Hitilafu
```

```
        <source>Error</source>
        <translation>Onyo</translation>
    
YES
The translation of "Error" as "Onyo" is incorrect. "Onyo" means "Warning" in Swahili.

Correct translation:
Hitilafu
```

```
        <source>More than one onion bind address is provided. Using %s for the automatically created Tor onion service.</source>
        <translation>Zaidi ya anuani moja ya onion bind imetolewa. Inatumia %skwa ajili ya huduma ya Tor onion inayotengeneza kiotomatiki. </translation>
    
YES
There is a missing space between '%s' and 'kwa', resulting in '%skwa'. Also, "inayoundwa kiotomatiki" is a more accurate rendering of "automatically created" (than 'inayotengeneza kiotomatiki', which is less idiomatic). Additionally, "inatumiwa kwa ajili ya" ("is used for") pairs better with "using".

Correct translation:
Zaidi ya anuani moja ya onion bind imetolewa. %s inatumiwa kwa ajili ya huduma ya Tor onion inayoundwa kiotomatiki.
```
</details>

Number of issues: 12.
