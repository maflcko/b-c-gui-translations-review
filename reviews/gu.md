# Translations Review by LLM (✨ experimental)

The review quality depends on the LLM and the language. Currently, a fast LLM without rate limits is used. If you are interested in better quality for a specific language, please file an issue to ask for it to be re-run with a stronger model.



<details><summary>gu</summary>

[If the result is of low quality, please file an issue to find a better LLM for this language.](../../issues/new?title=%5Bgu%5D%20low%20quality)


```
        <source>These are your Bitcoin addresses for sending payments. Always check the amount and the receiving address before sending coins.</source>
        <translation>આ તમારા ચુકવણી કરવા માટે ના સરનામાં છે, હંમેશા કિંમત અને મોકલવાના ના સરનામાં ચકાસી લેવા સિક્કા આપતા પહેલા.</translation>
    
YES  
The Gujarati translation contains grammatical errors and awkward phrasing that may confuse the reader. The phrase "ચુકવણી કરવા માટે ના સરનામા" should be "ચુકવણીઓ મોકલવા માટેના સરનામા" to sound natural and correct. Similarly, "મોકલવાના ના સરનામા" should be "પ્રાપ્ત કરવાના સરનામા." Also, "કિંમત" should be "રકમ" for "amount" in this context. The last part "ચકાસી લેવા સિક્કા આપતા પહેલા" is awkward and should be reordered for clarity.

Correct translation:  
"આ તમારા બિટકોઇન ચુકવણીઓ મોકલવા માટેના સરનામા છે. સિક્કા મોકલતાં પહેલાં હંમેશા રકમ અને પ્રાપ્ત કરવાના સરનામા તપાસો."
```

```
        <source>There was an error trying to save the address list to %1. Please try again.</source>
        <extracomment>An error message. %1 is a stand-in argument for the name of the file we attempted to save to.</extracomment>
        <translation>સરનામાં સૂચિને માં સાચવવાનો પ્રયાસ કરતી વખતે ભૂલ આવી હતી %1. મહેરબાની કરીને ફરીથી પ્રયતન કરો.</translation>
    
YES
The translation has a misplaced word order and missing proper spacing before the placeholder %1. In Gujarati, the phrase should have the file placeholder %1 placed appropriately, usually right after "સાચવવા માટે" (to save to). Also, the phrase "માં" (in/at) is out of place here.

Correct translation:
સરનામા સૂચિને %1માં સાચવવાનો પ્રયાસ કરતી વખતે ભૂલ આવી હતી. કૃપા કરીને ફરીથી પ્રયાસ કરો.
```

```
        <source>Receiving addresses - %1</source>
        <translation>સરનામુ લેવુ-%1</translation>
    
YES  
The translation does not accurately convey the meaning of "Receiving addresses - %1". The phrase "સરનામુ લેવુ" translates roughly as "taking address" or "to take address", which is not appropriate here. The source refers to addresses for receiving (Bitcoin) payments, so a better translation would explicitly indicate "Receiving addresses" as noun phrase with correct spacing and punctuation.

Correct translation:  
સ્વીકારતી સરનામાંઓ - %1
```

```
        <source>Passphrase Dialog</source>
        <translation>ગુપ્ત શબ્દ માટે નુ ડાયલોગ</translation>
    
YES
The translation contains extra spacing and incorrect phrasing. The phrase "નું ડાયલોગ" is incorrectly split as "નુ ડાયલોગ" and should be a single phrase "ડાયલોગ" preceded by correct possessive form. The correct translation omits unnecessary spacing and uses proper Gujarati possessive construct.

Correct translation:
ગુપ્ત શબ્દ સંવાદ
```

```
        <source>This operation needs your wallet passphrase to unlock the wallet.</source>
        <translation>પાકીટ અવલોકન જરુરી છે પાકીટ ઓપન કરવા માટે</translation>
    
YES  
The translation is inaccurate and incomplete. It wrongly uses "પાકીટ અવલોકન" (packet monitoring) instead of correctly translating "wallet passphrase" and does not mention unlocking the wallet correctly.

Correct translation:  
આ કાર્ય માટે તમારું વૉલેટ પાસફ્રેઝ જરૂર છે વૉલેટ અનલોક કરવા માટે.
```

```
        <source>Enter the new passphrase for the wallet.&lt;br/&gt;Please use a passphrase of &lt;b&gt;ten or more random characters&lt;/b&gt;, or &lt;b&gt;eight or more words&lt;/b&gt;.</source>
        <translation>વૉલેટ માટે નવો પાસફ્રેઝ દાખલ કરો. &lt;br&gt; કૃપા કરીને  &lt;b&gt; દસ અથવા વધુ અજાન્યા અક્ષરો &lt;/2&gt; અથવા &lt;b&gt; આઠ અથવા વધુ શબ્દોના પાસફ્રેઝનો ઉપયોગ કરો &lt;/b&gt; .</translation>
    
YES  
The translation contains HTML tag errors and spacing issues:  
- The line break tag `<br/>` in the source is translated as `<br>`, which is acceptable as HTML allows both, but to be consistent, `<br/>` is better.  
- There's a wrong closing tag `</2>` instead of `</b>` after "દસ અથવા વધુ અજાન્યા અક્ષરો".  
- Extra spaces before and after tags should be cleaned up, especially inside `<b>` tags.  
- The phrase "અજાન્યા અક્ષરો" (unknown characters) is a less accurate translation for "random characters". A better translation for "random characters" is "યાદૃછિક અક્ષરો" or "રેન્ડમ અક્ષરો".  

Correct translation:  
વૉલેટ માટે નવો પાસફ્રેઝ દાખલ કરો.&lt;br/&gt;કૃપા કરીને &lt;b&gt;દસ અથવા વધુ યાદૃછિક અક્ષરો&lt;/b&gt; અથવા &lt;b&gt;આઠ અથવા વધુ શબ્દો&lt;/b&gt;નો પાસફ્રેઝ વાપરો.
```

```
        <source>Feeler</source>
        <extracomment>Short-lived peer connection type that tests the aliveness of known addresses.</extracomment>
        <translation>ભરવા</translation>
    
YES
The English term "Feeler" in the Bitcoin context refers to a short-lived peer connection to test the availability ("aliveness") of known addresses. The Gujarati translation provided, "ભરવા", means "to fill" or "to fill up," which is incorrect in this context.

Correct translation:
"ફીલર" 
(or alternatively transliterating "Feeler" as "ફીલર" to maintain technical terminology clarity)
```

```
        <source>Connecting to peers…</source>
        <translation>સાથીદારોએ સાથે જોડાઈ…</translation>
    
YES  
The translation is incorrect and unnatural. The source English phrase "Connecting to peers…" is about the action of establishing connections to peers. The Gujarati translation "સાથીદારોએ સાથે જોડાઈ…" translates to "Peers joined together…" which is past tense and implies peers have already joined, not the ongoing action of connecting.

A better translation for "Connecting to peers…" in Gujarati would be:  
"સાથીદારો સાથે જોડાઈ રહ્યો છે…"  
or simply  
"સાથીદારો સાથે જોડાઈ રહ્યા છે…"  
to indicate the ongoing process of connecting.

Correct translation:  
<translation>સાથીદારો સાથે જોડાઈ રહ્યો છે…</translation>
```

```
        <source>Show</source>
        <translation> કેવી રીતે</translation>
    
YES  
The translation "કેટલી રીતે" means "how" or "in what way," which is incorrect for the English word "Show." The accurate translation for "Show" in Gujarati would be "પ્રદર્શન કરો" or simply "પ્રદર્શિત કરો."

Correct translation:  
<translation>પ્રદર્શન કરો</translation>
```

```
        <source>change from %1 (%2)</source>
        <translation>થી બદલો%1(%2)</translation>
    
YES  
The translation does not correctly preserve the spacing and natural word order in Gujarati. In particular, there should be a space after "થી" and before "%1", and the parentheses should be spaced properly. Also, the phrase "change from" is better translated as "બદલો %1 (%2) થી" or "થી بدلવો %1 (%2)" depending on context, but usually "change from %1 (%2)" means "બદલો %1 (%2) માંથી". 

A better translation would be:  
"બદલો %1 (%2) માંથી"  

If the word "થી" (meaning "from") is placed after "%2", it sounds more natural.  

So, the correct translation:  
<translation>બદલો %1 (%2) માંથી</translation>
```

```
        <source>As this is the first time the program is launched, you can choose where %1 will store its data.</source>
        <translation>આ પ્રથમ વખત પ્રોગ્રામ લોન્ચ થયો હોવાથી, , તમે પસંદ કરી શકો છો કે %1 તેનો ડેટા ક્યાં સંગ્રહિત કરશે</translation>
    
YES  
The translation contains a double comma ", ," which is a punctuation error. Additionally, the sentence ends abruptly without a proper full stop or completion in Gujarati. The sentence can be improved for clarity and correctness.

Correct translation:  
આ પ્રથમ વખત પ્રોગ્રામ શરૂ થઈ રહ્યો છે, તેથી તમે પસંદ કરી શકો છો કે %1 તેનું ડેટા ક્યાં સંગ્રહિત કરશે.
```

```
        <source>When you click OK, %1 will begin to download and process the full %4 block chain (%2 GB) starting with the earliest transactions in %3 when %4 initially launched.</source>
        <translation>જ્યારે તમે ઓકે ક્લિક કરો છો,%1સંપૂર્ણ ડાઉનલોડ અને પ્રક્રિયા કરવાનું શરૂ કરશે%4બ્લોક ચેન (સાંકળ) (%2GB) માં સૌથી પહેલાના વ્યવહારોથી શરૂ થાય છે%3જ્યારે%4શરૂઆતમાં લોન્ચ કર્યું.</translation>
    
YES  
The translation has spacing issues and some parts are awkward or incorrect. For example:  
- Missing spaces after commas and between words and placeholders (e.g., "જો તમે ઓકે ક્લિક કરો છો,%1સંપૂર્ણ" should have spaces).  
- The word "સાંકળ" (which means "chain" but usually in a different context) is placed in parentheses incorrectly. The source does not mention parentheses after "block chain".  
- The overall sentence structure is somewhat confusing and unnatural in Gujarati.  

Correct translation:  
જ્યારે તમે ઓકે ક્લિક કરો, ત્યારે %1 %4 પૂર્ણ બ્લોક ચેઇન (%2 GB) ડાઉનલોડ અને પ્રક્રિયા કરવાનું શરૂ કરશે, જે %4 ને શરૂઆતમાં લોન્ચ કર્યા પછી %3માં સૌથી પહેલાંના લેવદેવથી શરૂ થાય છે.
```

```
        <source>Unknown. Pre-syncing Headers (%1, %2%)…</source>
        <translation>અજ્ઞાત. પહેલાંથી સમન્વય હેડર્સ (%1,%2 %)…</translation>
    
YES  
There is a spacing issue with the format specifiers in the translation. In the source, "%1, %2%" has a space after the comma, but in the translation, it is shown as "(%1,%2 %)". The space after the comma is missing and the position of the % sign for %2 is incorrect (should be immediately after 2, without a space). Also, the ellipsis (…) is used correctly.  

Correct translation:  
અજ્ઞાત. પહેલાંથી સમન્વય હેડર્સ (%1, %2%)…
```

```
        <source>Number of script verification threads</source>
        <translation>સ્ક્રિપ્ટ અને ચકાસણી દોરિયોની સંખ્યા</translation>
    
YES  
The translation incorrectly adds "અને" (and) which is not present in the source text. The source text means "Number of script verification threads," where "script verification" is a compound descriptor. In the translation, " અને" means "and," causing a meaning distortion to "Number of script and verification threads," which is incorrect.  

Correct translation:  
સ્ક્રિપ્ટ ચકાસણી દોરિયોની સંખ્યા
```

```
        <source>Prune block storage to</source>
        <translation>સ્ટોરેજને કાપો અને અવરોધિત કરો</translation>
    
YES  
The translation "સ્ટોરેજને કાપો અને અવરોધિત કરો" means "Cut and block the storage," which adds the meaning of "blocking" that is not present in the source. The English phrase "Prune block storage to" refers specifically to reducing or trimming the block storage size, without suggesting blocking or obstructing it. Also, the phrase is incomplete as in English—it typically is followed by a size (e.g., "Prune block storage to %1 MB"). The translation should reflect pruning or trimming only.

Correct translation:  
"બ્લોક સ્ટોરેજ કાપો"
```

```
        <source>User Interface language:</source>
        <translation>વપરાશકર્તા ઈન્ટરફેસ અને ભાષા:</translation>
    
YES
The original English text "User Interface language:" refers specifically to the language setting of the user interface. However, the Gujarati translation "વપરાશકર્તા ઈન્ટરફેસ અને ભાષા:" means "User Interface and Language:", which adds an extra conjunction "and" and changes the meaning.

Correct translation:
વપરાશકર્તા ઈન્ટરફેસ ભાષા:
```

```
        <source>Unknown error processing transaction.</source>
        <translation>અજ્ઞાત ભૂલ પ્રક્રિયા વ્યવહાર વ્યવહાર.</translation>
    
YES
The translation is incorrect and contains a repetition of the word "વ્યવહાર" (transaction), making it nonsensical. The correct translation should be:

અજ્ઞાત ભૂલ વ્યવહાર પ્રક્રિયા દરમિયાન.
```

```
        <source>Sends %1 to %2</source>
        <translation>%1 , %2 ને મોકલે છે</translation>
    
YES  
The placement of the comma between %1 and %2 is incorrect and unnatural in Gujarati. The English phrase "Sends %1 to %2" indicates that %1 (e.g., an amount or object) is sent to %2 (e.g., an address or person). The correct Gujarati translation should directly connect %1 and %2 with the postposition "ને" (meaning "to"), without a comma between them.

Correct translation:  
%1 ને %2 માટે મોકલે છે  
or more simply,  
%1 ને %2 ને મોકલે છે  

But since "ને" is used for the indirect object, the more idiomatic sentence is:  
%1 ને %2 ને મોકલે છે  

Alternatively, the simplest and most commonly acceptable is:  
%1 ને %2 મોકલે છે

Hence, the correct translation is:  
%1 ને %2 મોકલે છે
```

```
        <source>Outbound</source>
        <extracomment>An Outbound Connection to a Peer.</extracomment>
        <translation>બહારનું </translation>
    
YES  
The Gujarati translation "બહારનું " has an unnecessary trailing space and uses a form that can be ambiguous or incomplete. The English term "Outbound" here is an adjective describing a connection (outbound connection). A better translation would be "બહારનું" without the trailing space or a more precise term like "બહાર જતું" which clearly means "going outside" or "outbound."

Correct translation:  
બહારનું
```

```
        <source>Elapsed time since a novel block passing initial validity checks was received from this peer.</source>
        <translation>આ પીઅર તરફથી પ્રારંભિક માન્યતા તપાસો પસાર કરતો નવલકથા બ્લોક પ્રાપ્ત થયો ત્યારથી વીત્યો સમય.</translation>
    
YES  
The translation has word choice issues and is somewhat unclear or unnatural in Gujarati. The phrase "નવલકથા બ્લોક" literally translates to "novel/story block," which is a literal but inappropriate translation for "novel block" in the technical Bitcoin context. A better choice is to use "નવા બ્લોક" (new block) or "નવ કોરા બ્લોક" (new block) which is more natural and understandable in technical Gujarati.

Also, "પ્રારંભિક માન્યતા તપાસો" ("validity checks") should be singular "પ્રારંભિક માન્યતા ચકાસણીઓ" (validity checks, plural) to match source's plural "checks."

Suggested corrected translation:  
"આ પીઅર તરફથી પ્રારંભિક માન્યતા ચકાસણીઓ પસાર કરતો નવો બ્લોક પ્રાપ્ત થયો ત્યારથી પસાર થયેલો સમય."
```

```
        <source>Elapsed time since a novel transaction accepted into our mempool was received from this peer.</source>
        <extracomment>Tooltip text for the Last Transaction field in the peer details area.</extracomment>
        <translation>અમારા મેમ્પૂલમાં સ્વીકારવામાં આવેલ નવલકથા વ્યવહારને આ પીઅર તરફથી પ્રાપ્ત થયો ત્યારથી વીત્યો સમય.</translation>
    
YES
The translation incorrectly uses "નવલકથા વ્યવહાર" which means "novel story transaction" instead of referring to a "novel (new) transaction". The phrase should convey "new or novel transaction" in the Bitcoin context, not "novel" as in literature.

Correct translation:
અમારા મેમ્પૂલમાં સ્વીકારેલા નવા વ્યવહાર આ પીઅર તરફથી મળ્યા ત્યારથી વિતેલા સમય.
```

```
        <source>v1: unencrypted, plaintext transport protocol</source>
        <extracomment>Explanatory text for v1 transport type.</extracomment>
        <translation>v1: એનક્રિપ્ટેડ, પ્લેનટેક્સ્ટ ટ્રાન્સપોર્ટ પ્રોટોકોલ</translation>
    
YES  
The translation incorrectly uses "એનક્રિપ્ટેડ" which means "encrypted," whereas the source says "unencrypted," meaning not encrypted. The correct Gujarati term for "unencrypted" would be "બિનએનક્રિપ્ટેડ" or "અનએનક્રિપ્ટેડ".  

Correct translation:  
v1: બિનએનક્રિપ્ટેડ, પ્લેનટેક્સ્ટ ટ્રાન્સપોર્ટ પ્રોટોકોલ
```
</details>
