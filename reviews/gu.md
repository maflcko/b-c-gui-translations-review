# Translations Review by LLM (✨ experimental)

The review quality depends on the LLM and the language. Currently, a fast LLM without rate limits is used. If you are interested in better quality for a specific language, please file an issue to ask for it to be re-run with a stronger model.



<details><summary>gu</summary>

[If the result is of low quality, please file an issue to find a better LLM for this language.](../../issues/new?title=%5Bgu%5D%20low%20quality)


```
        <source>These are your Bitcoin addresses for sending payments. Always check the amount and the receiving address before sending coins.</source>
        <translation>આ તમારા ચુકવણી કરવા માટે ના સરનામાં છે, હંમેશા કિંમત અને મોકલવાના ના સરનામાં ચકાસી લેવા સિક્કા આપતા પહેલા.</translation>
    
YES
The translation is understandable but has significant grammar errors and does not flow naturally in Gujarati. Also, "Bitcoin addresses" should be translated to "Bitcoin સરનામાઓ" to specify plurality, and the informational aspect of checking both amount and address is better stated.

Correct translation:
આ ચુકવણી મોકલવા માટે ваши Bitcoin સરનામાઓ છે. સિક્કા મોકલતાં પહેલાં હંમેશા રકમ અને પ્રાપ્તકર્તાનું સરનામું ચકાસો.
```

```
        <source>Receiving addresses - %1</source>
        <translation>સરનામુ લેવુ-%1</translation>
    
YES
The translation is inaccurate. The English "Receiving addresses - %1" should be correctly translated to Gujarati as "પ્રાપ્ત ہونے वाले સરનાનો - %1" or more properly "પ્રાપ્ત કરવાના સરનામા - %1". The given translation "સરનામુ લેવુ-%1" is incorrect, as it literally means "take address" and does not match the meaning.

Correct translation:
પ્રાપ્ત કરવાના સરનામા - %1
```

```
        <source>Passphrase Dialog</source>
        <translation>ગુપ્ત શબ્દ માટે નુ ડાયલોગ</translation>
    
YES
The translation is understandable but has minor linguistic issues. "ગુપ્ત શબ્દ માટે નુ ડાયલોગ" translates literally to "Dialog for passphrase," but the possessive is not standard Gujarati grammar. It would be better as: "પાસફ્રેઝ સંવાદ" or "પાસફ્રેઝ ડાયલોગ".

Correct translation:
પાસફ્રેઝ સંવાદ
```

```
        <source>This operation needs your wallet passphrase to unlock the wallet.</source>
        <translation>પાકીટ અવલોકન જરુરી છે પાકીટ ઓપન કરવા માટે</translation>
    
YES
The translation is inaccurate and does not convey the meaning of the source sentence. The source refers to needing the wallet passphrase to unlock the wallet. The translation says, "પાકીટ અવલોકન જરુરી છે પાકીટ ઓપન કરવાનો માટે" which means "Wallet observation is necessary to open the wallet," which is not correct.

Correct translation:
આ ઓપરેશન માટે તમારે વૉલેટ અનલોક કરવા વૉલેટ પાસફ્રેઝ અપાવવી જરૂર છે.
```

```
        <source>Enter the new passphrase for the wallet.&lt;br/&gt;Please use a passphrase of &lt;b&gt;ten or more random characters&lt;/b&gt;, or &lt;b&gt;eight or more words&lt;/b&gt;.</source>
        <translation>વૉલેટ માટે નવો પાસફ્રેઝ દાખલ કરો. &lt;br&gt; કૃપા કરીને  &lt;b&gt; દસ અથવા વધુ અજાન્યા અક્ષરો &lt;/2&gt; અથવા &lt;b&gt; આઠ અથવા વધુ શબ્દોના પાસફ્રેઝનો ઉપયોગ કરો &lt;/b&gt; .</translation>
    
YES
The translation contains several issues:
- Mismatched HTML tags: &lt;b&gt;...&lt;/2&gt; is incorrect; it should be &lt;/b&gt;.
- Redundant space characters before some tags and punctuation.
- The phrase "અજાન્યા અક્ષરો" is a less common form of "random characters"; "યાદગીરીથી ભરીલ" ('memorized') or "રૅન્ડમ" (transliteration) could be more understandable, but "અજાન્યા" is still understandable.
- The instruction should clearly reflect both the "ten or more random characters" and the "eight or more words" distinction.

Correct translation:
વૉલેટ માટે નવો પાસફ્રેઝ દાખલ કરો.&lt;br/&gt;કૃપા કરીને &lt;b&gt;દસ અથવા વધુ રૅન્ડમ અક્ષરો&lt;/b&gt; અથવા &lt;b&gt;આઠ અથવા વધુ શબ્દો&lt;/b&gt;નો પાસફ્રેઝ ઉપયોગ કરો.

Explanation: Fixed the mismatched tags, improved phrase clarity, corrected spacing, and more closely followed the source.
```

```
        <source>Feeler</source>
        <extracomment>Short-lived peer connection type that tests the aliveness of known addresses.</extracomment>
        <translation>ભરવા</translation>
    
YES
The translation "ભરવા" means "to fill" or "filling" in Gujarati, which does not accurately represent the technical term "Feeler" as used in the Bitcoin context. "Feeler" refers to a short-lived test connection, not something to be filled.

Correct translation:
ફીલર

Alternatively, if transliteration is not preferred:
ટેસ્ટ સંપર્ક (test connection)

So a suitable translation would be:
ફીલર

or

ટેસ્ટ સંપર્ક
```

```
        <source>Connecting to peers…</source>
        <translation>સાથીદારોએ સાથે જોડાઈ…</translation>
    
YES
The translation is inaccurate. The Gujarati translation "સાથીદારોએ સાથે જોડાઈ…" incorrectly uses the plural form and past tense, implying "Peers have joined (already)". The correct translation for "Connecting to peers…" (which is a present continuous action) would be:

સાથીઓ સાથે જોડાઈ રહ્યું છે…
```

```
        <source>Show</source>
        <translation> કેવી રીતે</translation>
    
YES
The translation "કેવી રીતે" means "how" in Gujarati, which is incorrect for the English word "Show". 

Correct translation:
દર્શન કરો
or
બતાવો
```

```
        <source>change from %1 (%2)</source>
        <translation>થી બદલો%1(%2)</translation>
    
YES
There is a formatting issue: there is no space between "બદલો" and %1. In Gujarati, it should read more naturally, and spacing should be considered. Also, the preposition order can be improved.

Correct translation:
%1 (%2) માંથી ફેરફાર

Or more literally retaining the structure:
%1 (%2) માંથી બદલાવ

Note: "ફેરફાર" or "બદલાવ" both are valid for "change". The original translation also omits the word "change" at the correct place.
```

```
        <source>As this is the first time the program is launched, you can choose where %1 will store its data.</source>
        <translation>આ પ્રથમ વખત પ્રોગ્રામ લોન્ચ થયો હોવાથી, , તમે પસંદ કરી શકો છો કે %1 તેનો ડેટા ક્યાં સંગ્રહિત કરશે</translation>
    
YES
There is a punctuation error: there are two commas after "આ પ્રથમ વખત પ્રોગ્રામ લોન્ચ થયો હોવાથી," which is incorrect. Also, the sentence could flow better in Gujarati.

Correct translation:
આ پہلی વખત પ્રોગ્રામ લોન્ચ થયું છે, કારણ કે તમે પસંદ કરી શકો છો કે %1 તેની માહિતી ક્યાં સંગ્રહિત કરશે.

Or to correct the original with minimal change:
આ પ્રથમ વખત પ્રોગ્રામ લોન્ચ થયો હોવાથી, તમે પસંદ કરી શકો છો કે %1 તેનો ડેટા ક્યાં સંગ્રહિત કરશે.
```

```
        <source>When you click OK, %1 will begin to download and process the full %4 block chain (%2 GB) starting with the earliest transactions in %3 when %4 initially launched.</source>
        <translation>જ્યારે તમે ઓકે ક્લિક કરો છો,%1સંપૂર્ણ ડાઉનલોડ અને પ્રક્રિયા કરવાનું શરૂ કરશે%4બ્લોક ચેન (સાંકળ) (%2GB) માં સૌથી પહેલાના વ્યવહારોથી શરૂ થાય છે%3જ્યારે%4શરૂઆતમાં લોન્ચ કર્યું.</translation>
    
YES
There are issues with spacing—missing spaces after commas and around format specifiers (%1, %4, etc.), which impacts readability. Also, some word ordering could be improved for natural Gujarati.

Correct translation:
જ્યારે તમે ઓકે ક્લિક કરો છો, %1 સંપૂર્ણ %4 બ્લોક ચેન (%2 GB) ડાઉનલોડ અને પ્રક્રિયા કરવાનું શરૂ કરશે, જે %3 માં %4 જ્યારે પ્રથમ લોન્ચ થયું હતું ત્યારે સૌથી પુરાતન વ્યવહારોથી શરૂ કરશે.
```

```
        <source>Unknown. Pre-syncing Headers (%1, %2%)…</source>
        <translation>અજ્ઞાત. પહેલાંથી સમન્વય હેડર્સ (%1,%2 %)…</translation>
    
YES
There are minor issues:

1. The Gujarati translation adds an unnecessary space between '%2' and '%' ("%2 %"), whereas the source keeps '%2%'.
2. There is a missing space after the comma inside the parentheses between '%1' and '%2%'.

Correct translation:
અજ્ઞાત. પૂર્વ-સિંન્ક હેડર્સ (%1, %2%)…
```

```
        <source>Number of script verification threads</source>
        <translation>સ્ક્રિપ્ટ અને ચકાસણી દોરિયોની સંખ્યા</translation>
    
YES
The translation inaccurately adds "અને" (and) which is not in the source, and "દોરિયોની" is a misspelling of "થ્રેડ્સ" (threads). The translation also does not properly reflect "script verification threads".

Correct translation:
સ્ક્રિપ્ટ ચકાસણી થ્રેડ્સની સંખ્યા
```

```
        <source>Prune block storage to</source>
        <translation>સ્ટોરેજને કાપો અને અવરોધિત કરો</translation>
    
YES
The translation "સ્ટોરેજને કાપો અને અવરોધિત કરો" is inaccurate. The word "Prune" in this Bitcoin context refers specifically to reducing the size of stored blockchain data—i.e., deleting old block data to save space. The Gujarati translation introduces the idea of "blocking" (અવરોધિત કરો), which is not present in the source.

Correct translation:
બ્લોક સ્ટોરેજને કાપો

Or more fully:
બ્લોક સ્ટોરેજને કાપી નાખો

Either version would be more accurate.
```

```
        <source>User Interface language:</source>
        <translation>વપરાશકર્તા ઈન્ટરફેસ અને ભાષા:</translation>
    
YES
The translation is not accurate. The English phrase is "User Interface language:" which refers specifically to the language used for the user interface, not "User Interface and language:" as in the Gujarati translation.

Correct translation:
વપરાશકર્તા ઈન્ટરફેસ ભાષા:
```

```
        <source>Unknown error processing transaction.</source>
        <translation>અજ્ઞાત ભૂલ પ્રક્રિયા વ્યવહાર વ્યવહાર.</translation>
    
YES
The translation repeats the word "વ્યવહાર" (transaction) twice and has an unnatural phrasing. The correct translation should be:

Correct translation:
અજ્ઞાત ભૂલ દરમિયાન વ્યવહારની પ્રક્રિયા થઈ.
```

```
        <source>Outbound</source>
        <extracomment>An Outbound Connection to a Peer.</extracomment>
        <translation>બહારનું </translation>
    
YES
There is an unnecessary trailing space in the translation, and the Gujarati rendering is a bit awkward. More contextually, a better translation for "Outbound" in the context of a Bitcoin network (connection to a Peer) would be "બાહ્ય". So, the translation should avoid the informal form and trailing space.

Correct translation:
બાહ્ય
```

```
        <source>Elapsed time since a novel transaction accepted into our mempool was received from this peer.</source>
        <extracomment>Tooltip text for the Last Transaction field in the peer details area.</extracomment>
        <translation>અમારા મેમ્પૂલમાં સ્વીકારવામાં આવેલ નવલકથા વ્યવહારને આ પીઅર તરફથી પ્રાપ્ત થયો ત્યારથી વીત્યો સમય.</translation>
    
YES
The translation incorrectly translates "novel transaction" as "નવલકથા વ્યવહાર", where "નવલકથા" means "novel" as in a literary work. The intended meaning is "new" or "recent" transaction, so the correct translation should use "નવું" or "નવી".

Correct translation:
અમારા મેમ્પૂલમાં સ્વીકારવામાં આવેલા નવા વ્યવહાર આ પીઅર તરફથી પ્રાપ્ત થયા પછી વીતી ગયેલ સમય.
```

```
        <source>v1: unencrypted, plaintext transport protocol</source>
        <extracomment>Explanatory text for v1 transport type.</extracomment>
        <translation>v1: એનક્રિપ્ટેડ, પ્લેનટેક્સ્ટ ટ્રાન્સપોર્ટ પ્રોટોકોલ</translation>
    
YES
The translation is problematic. The English source states "unencrypted," but the Gujarati translation writes "એનક્રિપ્ટેડ" which means "encrypted," reversing the original meaning. It should use the correct opposite meaning.

Correct translation:
v1: અનએનક્રિપ્ટેડ, પ્લેનટેક્સ્ટ ટ્રાન્સપોર્ટ પ્રોટોકોલ
```
</details>

Number of issues: 19.
