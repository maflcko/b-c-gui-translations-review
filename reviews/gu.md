# Translations Review by LLM (✨ experimental)

The review quality depends on the LLM and the language. Currently, a fast LLM without rate limits is used. If you are interested in better quality for a specific language, please file an issue to ask for it to be re-run with a stronger model.



<details><summary>gu</summary>

[If the result is of low quality, please file an issue to find a better LLM for this language.](../../issues/new?title=%5Bgu%5D%20low%20quality)


```
        <source>These are your Bitcoin addresses for sending payments. Always check the amount and the receiving address before sending coins.</source>
        <translation>આ તમારા ચુકવણી કરવા માટે ના સરનામાં છે, હંમેશા કિંમત અને મોકલવાના ના સરનામાં ચકાસી લેવા સિક્કા આપતા પહેલા.</translation>
    
YES
The word order is unnatural and grammatically incorrect in Gujarati.

Correct translation: આ તમારા ચુકવણી કરવા માટેના બીટકોઈન સરનામાં છે. સિક્કા મોકલતા પહેલા હંમેશા રકમ અને મેળવનારનું સરનામું તપાસો.
```

```
        <source>There was an error trying to save the address list to %1. Please try again.</source>
        <extracomment>An error message. %1 is a stand-in argument for the name of the file we attempted to save to.</extracomment>
        <translation>સરનામાં સૂચિને માં સાચવવાનો પ્રયાસ કરતી વખતે ભૂલ આવી હતી %1. મહેરબાની કરીને ફરીથી પ્રયતન કરો.</translation>
    
YES: The word order in the Gujarati translation is incorrect. The phrase "સરનામાં સૂચિને માં સાચવવાનો પ્રયાસ કરતી વખતે ભૂલ આવી હતી %1" translates to "an error occurred while trying to save the address list to %1". A more natural and grammatically correct phrasing would be "સરનામાં સૂચિને %1 માં સાચવવાનો પ્રયાસ કરતી વખતે ભૂલ આવી હતી".

Correct translation: સરનામાં સૂચિને %1 માં સાચવવાનો પ્રયાસ કરતી વખતે ભૂલ આવી હતી.
```

```
        <source>Receiving addresses - %1</source>
        <translation>સરનામુ લેવુ-%1</translation>
    
YES. The translation uses an incorrect word for "Receiving". Also, there is a missing space between "address" and the format specifier. The correct translation should be "મેળવતા સરનામાં - %1".

NO
```

```
        <source>Passphrase Dialog</source>
        <translation>ગુપ્ત શબ્દ માટે નુ ડાયલોગ</translation>
    
YES
The translation is not accurate. "Passphrase Dialog" translates to "પાસફ્રેઝ ડાયલોગ" in Gujarati.
પાસફ્રેઝ ડાયલોગ
```

```
        <source>This operation needs your wallet passphrase to unlock the wallet.</source>
        <translation>પાકીટ અવલોકન જરુરી છે પાકીટ ઓપન કરવા માટે</translation>
    
YES: The translation is inaccurate and doesn't convey the original meaning. The phrase "પાકીટ અવલોકન જરુરી છે" translates to "wallet observation is necessary," which is not related to unlocking a wallet. The correct translation should mention the passphrase.

NO
```

```
        <source>Confirm wallet encryption</source>
        <translation>એન્ક્રિપ્શન ખાતરી કરો </translation>
    
YES
The translation is missing the word "wallet" from the source text.
Correct translation: વોલેટ એન્ક્રિપ્શનની પુષ્ટિ કરો
```

```
        <source>Enter the new passphrase for the wallet.&lt;br/&gt;Please use a passphrase of &lt;b&gt;ten or more random characters&lt;/b&gt;, or &lt;b&gt;eight or more words&lt;/b&gt;.</source>
        <translation>વૉલેટ માટે નવો પાસફ્રેઝ દાખલ કરો. &lt;br&gt; કૃપા કરીને  &lt;b&gt; દસ અથવા વધુ અજાન્યા અક્ષરો &lt;/2&gt; અથવા &lt;b&gt; આઠ અથવા વધુ શબ્દોના પાસફ્રેઝનો ઉપયોગ કરો &lt;/b&gt; .</translation>
    
YES: The formatting of the bold tags is incorrect. The closing tag for "ten or more random characters" should be `</b>`, not `</b>`.
વૉલેટ માટે નવો પાસફ્રેઝ દાખલ કરો. &lt;br/&gt; કૃપા કરીને &lt;b&gt; દસ અથવા વધુ અજાન્યા અક્ષરો &lt;/b&gt; અથવા &lt;b&gt; આઠ અથવા વધુ શબ્દોના પાસફ્રેઝનો ઉપયોગ કરો &lt;/b&gt;.
```

```
        <source>Manual</source>
        <extracomment>Peer connection type established manually through one of several methods.</extracomment>
        <translation>માનવ સંચાલિત</translation>
    
YES
The translation "માનવ સંચાલિત" means "human operated". The English source "Manual" in the context of Bitcoin refers to a manual process rather than a human operator. A more accurate translation would be "મેન્યુઅલ".

Manual
મેન્યુઅલ
```

```
        <source>Feeler</source>
        <extracomment>Short-lived peer connection type that tests the aliveness of known addresses.</extracomment>
        <translation>ભરવા</translation>
    
YES
The translation "ભરવા" (bharva) is incorrect. It means "to fill" or "to stuff," which is not related to the concept of a "feeler" in the context of Bitcoin peer connections. The correct translation for "feeler" in this context would be "અનુભવનાર" (anubhavnar) which means "feeler" or "tester".

Correct translation: અનુભવનાર
```

```
        <source>Connecting to peers…</source>
        <translation>સાથીદારોએ સાથે જોડાઈ…</translation>
    
YES
The translation is grammatically incorrect and does not accurately convey the meaning of the source text. The phrase "સાથીદારોએ સાથે જોડાઈ" literally translates to "The companions joined together", which is not what the original English sentence "Connecting to peers…" means. The correct translation should convey the idea of establishing connections with other nodes on the Bitcoin network.

Correct translation: પીઅર્સ સાથે જોડાઈ રહ્યું છે…
```

```
        <source>Show</source>
        <translation> કેવી રીતે</translation>
    
YES. The translation is incorrect. The Gujarati word "કેવી રીતે" means "how", which does not match the English word "Show".

Correct translation: બતાવો
```

```
        <source>change from %1 (%2)</source>
        <translation>થી બદલો%1(%2)</translation>
    
YES. The translation is problematic as it is not idiomatic Gujarati. The word "થી" (thi) meaning "from" is placed at the beginning of the phrase, which is grammatically incorrect. Also, "બદલો" (badalo) which means "change" is placed after "થી", and the order of the words is reversed.

Correct translation: %1 (%2) માંથી બદલાવ
The word "માં" (mā) is used instead of "થી" (thi) as it indicates "from the amount" or "change within". "બદલાવ" (badalāv) is a more appropriate word for "change" in this context.

NO. The translation is not problematic. It is a direct and accurate translation of the source text, preserving the format specifiers. The Gujarati sentence "થી બદલો%1(%2)" translates to "change from %1 (%2)" and is contextually appropriate for Bitcoin transactions.
```

```
        <source>As this is the first time the program is launched, you can choose where %1 will store its data.</source>
        <translation>આ પ્રથમ વખત પ્રોગ્રામ લોન્ચ થયો હોવાથી, , તમે પસંદ કરી શકો છો કે %1 તેનો ડેટા ક્યાં સંગ્રહિત કરશે</translation>
    
YES, There is an extra comma in the translation.
આ પ્રથમ વખત પ્રોગ્રામ લોન્ચ થયો હોવાથી, તમે પસંદ કરી શકો છો કે %1 તેનો ડેટા ક્યાં સંગ્રહિત કરશે
```

```
        <source>When you click OK, %1 will begin to download and process the full %4 block chain (%2 GB) starting with the earliest transactions in %3 when %4 initially launched.</source>
        <translation>જ્યારે તમે ઓકે ક્લિક કરો છો,%1સંપૂર્ણ ડાઉનલોડ અને પ્રક્રિયા કરવાનું શરૂ કરશે%4બ્લોક ચેન (સાંકળ) (%2GB) માં સૌથી પહેલાના વ્યવહારોથી શરૂ થાય છે%3જ્યારે%4શરૂઆતમાં લોન્ચ કર્યું.</translation>
    
YES: The translation has several issues. The word order is incorrect, and some words are missing or misplaced, leading to a grammatically incorrect and nonsensical sentence. The format specifiers are also not correctly transferred.

Correct translation: જ્યારે તમે OK પર ક્લિક કરશો, ત્યારે %1 %4 બ્લોકચેન (%2 GB) ડાઉનલોડ અને પ્રોસેસ કરવાનું શરૂ કરશે, જેમાં %4 શરૂઆતમાં લોન્ચ થયું ત્યારથી શરૂ કરીને %3 માં સૌથી જૂના ટ્રાન્ઝેક્શનથી પ્રક્રિયા કરવામાં આવશે.
```

```
        <source>Unknown. Pre-syncing Headers (%1, %2%)…</source>
        <translation>અજ્ઞાત. પહેલાંથી સમન્વય હેડર્સ (%1,%2 %)…</translation>
    
YES - The spacing around the %2 in the translation is incorrect. It should match the source.
અજ્ઞાત. પહેલાંથી સમન્વય હેડર્સ (%1, %2%)…
```

```
        <source>Number of script verification threads</source>
        <translation>સ્ક્રિપ્ટ અને ચકાસણી દોરિયોની સંખ્યા</translation>
    
YES: The translation uses "અને" (and) which is not present in the source. The correct translation should be "સ્ક્રિપ્ટ ચકાસણી થ્રેડોની સંખ્યા".
```

```
        <source>Prune block storage to</source>
        <translation>સ્ટોરેજને કાપો અને અવરોધિત કરો</translation>
    
YES: The translation is inaccurate and doesn't convey the intended meaning of pruning block storage. The Gujarati translation "સ્ટોરેજને કાપો અને અવરોધિત કરો" means "Cut and block the storage," which is not the technical meaning of pruning in the context of Bitcoin block storage. Pruning in this context means removing older, unspent transaction outputs (UTXOs) to reduce the size of the blockchain data.

Correct translation: બ્લોક સ્ટોરેજને કાપો
```

```
        <source>User Interface language:</source>
        <translation>વપરાશકર્તા ઈન્ટરફેસ અને ભાષા:</translation>
    
YES, The translation is problematic because it adds "and language" to the original English text, which changes the meaning.

NO
```

```
        <source>Unknown error processing transaction.</source>
        <translation>અજ્ઞાત ભૂલ પ્રક્રિયા વ્યવહાર વ્યવહાર.</translation>
    
YES, The translation is problematic because it is repetitive. The word "વ્યવહાર" (transaction) is repeated twice.
Correct translation: અજ્ઞાત ભૂલ પ્રક્રિયા વ્યવહાર.
```

```
        <source>Sends %1 to %2</source>
        <translation>%1 , %2 ને મોકલે છે</translation>
    
YES, The translation is problematic because of the word order. The correct translation should be "%1 %2 ને મોકલે છે".

NO
```

```
        <source>Outbound</source>
        <extracomment>An Outbound Connection to a Peer.</extracomment>
        <translation>બહારનું </translation>
    
YES
The translation is incomplete and does not capture the meaning of "Outbound" in the context of a Bitcoin connection. The provided translation "બહારનું " literally means "external" or "outer" and lacks the directional aspect of "outbound" when referring to a connection.

The correct translation should convey the idea of sending something out or an outgoing connection. A more appropriate translation would be:

<translation>આઉટબાઉન્ડ</translation>
```

```
        <source>Elapsed time since a novel block passing initial validity checks was received from this peer.</source>
        <translation>આ પીઅર તરફથી પ્રારંભિક માન્યતા તપાસો પસાર કરતો નવલકથા બ્લોક પ્રાપ્ત થયો ત્યારથી વીત્યો સમય.</translation>
    
YES
The Gujarati translation uses the word "નવલકથા" (navalkatha) which means "novel" or "fiction". This word is inappropriate in the context of Bitcoin blocks. A more suitable word would be "નવો" (navo) which means "new".

NO
```

```
        <source>Elapsed time since a novel transaction accepted into our mempool was received from this peer.</source>
        <extracomment>Tooltip text for the Last Transaction field in the peer details area.</extracomment>
        <translation>અમારા મેમ્પૂલમાં સ્વીકારવામાં આવેલ નવલકથા વ્યવહારને આ પીઅર તરફથી પ્રાપ્ત થયો ત્યારથી વીત્યો સમય.</translation>
    
YES, The translation is problematic. The word "નવલકથા" (navalkatha) means "novel" in the sense of a story or book, which is not the intended meaning in this context. The English word "novel" here means "new" or "recent".

Here's the corrected translation:
<translation>આ પીઅર પાસેથી અમારા મેમ્પૂલમાં સ્વીકારવામાં આવેલ નવા વ્યવહારને પ્રાપ્ત થયા ત્યારથી વીત્યો સમય.</translation>
```

```
        <source>v1: unencrypted, plaintext transport protocol</source>
        <extracomment>Explanatory text for v1 transport type.</extracomment>
        <translation>v1: એનક્રિપ્ટેડ, પ્લેનટેક્સ્ટ ટ્રાન્સપોર્ટ પ્રોટોકોલ</translation>
    
YES
The translation incorrectly states "encrypted" instead of "unencrypted".
v1: અનએનક્રિપ્ટેડ, પ્લેનટેક્સ્ટ ટ્રાન્સપોર્ટ પ્રોટોકોલ
```

```
        <source>Welcome to the %1 RPC console.
Use up and down arrows to navigate history, and %2 to clear screen.
Use %3 and %4 to increase or decrease the font size.
Type %5 for an overview of available commands.
For more information on using this console, type %6.

%7WARNING: Scammers have been active, telling users to type commands here, stealing their wallet contents. Do not use this console without fully understanding the ramifications of a command.%8</source>
        <extracomment>RPC console welcome message. Placeholders %7 and %8 are style tags for the warning content, and they are not space separated from the rest of the text intentionally.</extracomment>
        <translation>%1 RPC કન્સોલ પર આપનું સ્વાગત છે.
ઇતિહાસ નેવિગેટ કરવા માટે ઉપર અને નીચે તીરોનો ઉપયોગ કરો અને સ્ક્રીન સાફ કરવા માટે %2 નો ઉપયોગ કરો.
ફોન્ટનું કદ વધારવા અથવા ઘટાડવા માટે %3 અને %4 નો ઉપયોગ કરો.
ઉપલબ્ધ આદેશોની ઝાંખી માટે %5 લખો.
આ કન્સોલનો ઉપયોગ કરવા પર વધુ માહિતી માટે, %6 લખો.

%7 ચેતવણી: સ્કેમર્સ સક્રિય છે, વપરાશકર્તાઓને અહીં આદેશો લખવાનું કહે છે, તેમના વૉલેટની સામગ્રી ચોરી કરે છે. આ કન્સોલનો ઉપયોગ કમાન્ડની અસરને સંપૂર્ણપણે સમજ્યા વિના કરશો નહીં. %8</translation>
    
YES: The translation for "%7WARNING: Scammers have been active, telling users to type commands here, stealing their wallet contents. Do not use this console without fully understanding the ramifications of a command.%8" is not accurate. The Gujarati translation states "Scammers have been active, telling users to type commands here, stealing their wallet contents." and "Do not use this console without fully understanding the ramifications of a command." which is an incomplete translation of the original English text.

Correct translation:
%7ચેતવણી: સ્કેમર્સ સક્રિય રહ્યા છે, વપરાશકર્તાઓને અહીં આદેશો ટાઇપ કરવા કહે છે, તેમના વૉલેટની સામગ્રી ચોરી કરે છે. આ કન્સોલનો ઉપયોગ કમાન્ડની અસરને સંપૂર્ણપણે સમજ્યા વિના કરશો નહીં. %8
```
</details>
