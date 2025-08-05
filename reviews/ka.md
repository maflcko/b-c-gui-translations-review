# Translations Review by LLM (✨ experimental)

The review quality depends on the LLM and the language. Currently, a fast LLM without rate limits is used. If you are interested in better quality for a specific language, please file an issue to ask for it to be re-run with a stronger model.



<details><summary>ka</summary>

[If the result is of low quality, please file an issue to find a better LLM for this language.](../../issues/new?title=%5Bka%5D%20low%20quality)


```
        <source>Passphrase Dialog</source>
        <translation>საიდუმლო ფრაზის მიმოცვლა</translation>
    
YES
The Georgian phrase "საიდუმლო ფრაზის მიმოცვლა" literally means "secret phrase exchange," which misrepresents "Passphrase Dialog." The correct translation should convey that this is a dialog window related to the passphrase.

Correct translation:
პაროლის ფრაზის დიალოგი
```

```
        <source>Enter the new passphrase for the wallet.&lt;br/&gt;Please use a passphrase of &lt;b&gt;ten or more random characters&lt;/b&gt;, or &lt;b&gt;eight or more words&lt;/b&gt;.</source>
        <translation>შეიყვანეთ საფულის ახალი საიდუმლო ფრაზა .1 გამოიყენეთ მე –2 ან მეტი შემთხვევითი სიმბოლოების 2 ან 3 – ზე მეტი რვა ან მეტი სიტყვის პაროლი 3.</translation>
    
YES  
The translation is incoherent, contains extraneous characters (".1", "მე –2", "2 ან 3 – ზე მეტი", "3."), and does not accurately render the original message. It also misses the HTML formatting cues and the instruction is unclear.

Correct translation:  
შეიყვანეთ საფულის ახალი საიდუმლო ფრაზა.&lt;br/&gt;გთხოვთ გამოიყენოთ&gt;&lt;b&gt;ათი ან მეტი შემთხვევითი სიმბოლო&lt;/b&gt;, ან &lt;b&gt;რვა ან მეტი სიტყვა&lt;/b&gt;.
```

```
        <source>Remember that encrypting your wallet cannot fully protect your bitcoins from being stolen by malware infecting your computer.</source>
        <translation>გახსოვდეთ, რომ თქვენი საფულის დაშიფვრა ვერ უზრუნველყოფს სრულად დაიცვას თქვენი ბიტკოინების მოპარვა კომპიუტერში მავნე პროგრამებით.</translation>
    
YES  
The Georgian translation is awkward and contains grammatical errors. The phrase "არ უზრუნველყოფს სრულად დაიცვას" is incorrect and awkwardly structured. The phrase should be reworded for naturalness and correctness.

Correct translation:  
გახსოვდეთ, რომ თქვენი საფულის დაშიფვრა ვერ უზრუნველყოფს თქვენს ბიტკოინებზე სრულყოფილ დაცვას კომპიუტერში მავნე პროგრამების მიერ მოპარვისგან.
```

```
        <source>Wallet to be encrypted</source>
        <translation>დაშიფრულია საფულე</translation>
    
YES  
The translation "დაშიფრულია საფულე" means "The wallet is encrypted," which changes the meaning of the original English text "Wallet to be encrypted" (indicating it is about a wallet that needs to be encrypted, not one that already is). This changes the intent from future or imperative to a present state, which is incorrect.  

Correct translation:  
საფულე გასათიშავია  
(or more explicitly: საფულე, რომელიც უნდა დაიშიფროს)
```

```
        <source>Your wallet is about to be encrypted. </source>
        <translation>თქვენი საფულე იშიფრება</translation>
    
YES  
The source text "Your wallet is about to be encrypted." implies a future or imminent action, while the translation "თქვენი საფულე იშიფრება" means "Your wallet is being encrypted" (present continuous), which changes the meaning. Also, there is an extra space at the end of the English source that is not reflected in the translation, though this is minor.

A more accurate translation capturing the future aspect would be:  
"თქვენი საფულე მალე დაიშიფრება"  
(literally: "Your wallet will soon be encrypted") or  
"თქვენი საფულე მალე დაიკონტროლება" (less common).

Preferred correction:  
<translation>თქვენი საფულე მალე დაიშიფრება.</translation>
```

```
        <source>Banned Until</source>
        <translation>სანამ აიკრძალა</translation>
    
YES  
The translation "სანამ აიკრძალა" means "until it was banned" or "while it was banned," which does not convey the intended meaning of "Banned Until" as a label indicating a time or date until which something is banned. A more accurate translation would be:

"აკრძალულია მანამდე" or "აკრძალული სანამ"  

However, the most natural and clear translation for "Banned Until" in Georgian in this context is:

"აკრძალულია დრომდე"
```

```
        <source>Minimize</source>
        <translation>ჩახურვა</translation>
    
YES
The translation "ჩახურვა" means "close" rather than "minimize." The correct Georgian translation for "Minimize" in a computer/window context is "მინიმიზაცია" or "ჩანცვლა" (less common). 

Correct translation:
მინიმიზაცია
```

```
        <source>Sign message…</source>
        <translation>ხელმოწერა შეტყობინება…</translation>
    
YES  
The translation "ხელმოწერა შეტყობინება…" literally means "signature message…" or "sign message" in a noun form, which is not the correct imperative form for "Sign message…". The correct translation should use the verb form instructing the user to sign a message.  

Correct translation:  
"შეტყობინებაზე ხელმოწერა…"
```

```
        <source>Click for more actions.</source>
        <extracomment>A substring of the tooltip. "More actions" are available via the context menu.</extracomment>
        <translation>მეტი...</translation>
    
YES  
The translation "მეტი..." means "More..." and does not convey the full meaning of "Click for more actions." The source instructs the user to click to see more actions, not just indicating "more". A better translation would explicitly include the action of clicking, for example:

Correct translation:  
"დაწკაპეთ მეტი მოქმედებებისთვის."
```

```
        <source>Sent transaction</source>
        <translation>გაგზავნილი ტრანსაქციები</translation>
    
YES  
The source text "Sent transaction" is singular, but the translation "გაგზავნილი ტრანსაქციები" is plural ("transactions"). The correct singular form in Georgian would be:  
გაგზავნილი ტრანსაქცია
```

```
        <source>Coin Selection</source>
        <translation>Coin-ები</translation>
    
YES
The translation "Coin-ები" is a mixed-language form combining English "Coin" with the Georgian plural suffix "-ები," which is not appropriate. The correct Georgian translation for "Coin Selection" would be a proper noun phrase or a meaningful term in Georgian. A suitable translation could be:

მონეტების არჩევანი
```

```
        <source>After Fee:</source>
        <translation>დამატებითი საკომისიო:</translation>
    
YES  
The English phrase "After Fee:" indicates an amount or value remaining after subtracting a fee. The provided Georgian translation "დამატებითი საკომისიო:" means "Additional fee:", which changes the meaning significantly. A more accurate translation preserving the original meaning would be:

საკომისიოს შემდეგ:
```

```
        <source>Copy label</source>
        <translation>კოპირება ჭდე</translation>
    
YES  
The Georgian word "ჭდე" means "knot" or "bundle," which is incorrect for translating "label" in this context. The proper word for "label" (as used in Bitcoin wallet labels) is "ნიშანი" or more commonly "ლეგენდა" or simply "ლაბელა" (a transliteration). A suitable translation would be:  

კოპირება ლეიბელის or კოპირება ნიშნის  

Correct translation:  
კოპირება ლეიბელის
```

```
        <source>Copy transaction ID and output index</source>
        <translation>ტრანზაქციის კოპირება ID და ინდექსის გამოტანა</translation>
    
YES
The translation is inaccurate and awkward. The phrase "Copy transaction ID and output index" should be translated in a way that clearly commands copying both elements, not partially copying one and "outputting" the other.

Correct translation:
ტრანზაქციის ID-სა და გამოტანის ინდექსის კოპირება
```

```
        <source>Copy after fee</source>
        <translation>დამატებითი საკომისიოს კოპირება</translation>
    
YES  
The translation "დამატებითი საკომისიოს კოპირება" literally means "Copy of the additional fee," which does not accurately represent the English phrase "Copy after fee." In the Bitcoin context, "Copy after fee" likely means copying the amount or value after deducting the fee, or referring to the amount remaining after the fee. The Georgian translation should reflect that the copying is done of the value "after the fee" and not copying the fee itself.

A better translation would be:  
"საკომისიოდან შემდგომი კოპირება"  
or  
"ფულის გადახდის შემდეგ კოპირება" (Copying after payment of the fee)

Depending on the most concise and common terminology in the context, the first is preferred.

Correct translation:  
<translation>საკომისიოდან შემდგომი კოპირება</translation>
```

```
        <source>Are you sure you wish to close the wallet &lt;i&gt;%1&lt;/i&gt;?</source>
        <translation>დაიხუროს საფულე&lt;i&gt;%1&lt;/i&gt; ?</translation>
    
YES  
The Georgian translation misses the polite/formal phrasing corresponding to "Are you sure you wish to close...?" and contains incorrect spacing before the question mark in Georgian punctuation style (in Georgian, there is no space before the question mark). Also, the subject is omitted (it literally means "Close the wallet %1?"), losing the nuance of "Are you sure you wish to...?"

Correct translation:  
"დარწმუნებული ხართ, რომ გსურთ დახუროთ საფულე&lt;i&gt;%1&lt;/i&gt;?"
```

```
        <source>Encrypt Wallet</source>
        <translation>საფულის დაცვა [Encrypt Wallet]</translation>
    
YES  
The translation includes the original English text "[Encrypt Wallet]" unnecessarily, which is not typical or appropriate in a translation. The phrase "საფულის დაცვა" translates to "Wallet protection," which is close but not exact. A more precise Georgian translation of "Encrypt Wallet" would be "საფულის დაშიფვრა."

Correct translation:  
საფულის დაშიფვრა
```

```
        <source>Create</source>
        <translation>ახალი</translation>
    
YES  
The English word "Create" means to make or produce something. The Georgian translation "ახალი" means "new," which is incorrect in this context.  

Correct translation:  
შექმნა
```

```
        <source>Error: Specified data directory "%1" cannot be created.</source>
        <translation>შეცდომა: მითითებულ მონაცემთა დირექტორია „%1“ არ არის შექმნილი.</translation>
    
YES  
The translation incorrectly uses "არ არის შექმნილი" which means "is not created" or "has not been created," implying a current state, rather than an inability to create the directory. The English source indicates an error because the directory cannot be created, i.e., the creation attempt failed.

Correct translation:  
შეცდომა: მითითებული მონაცემთა დირექტორია „%1“ არ არის შესაძლებელი შექმნა.  

Alternatively, a more natural phrasing:  
შეცდომა: მითითებულ მონაცემთა დირექტორიას „%1“ შექმნა შეუძლებელია.
```

```
        <source>%1 is shutting down…</source>
        <translation> დახურულია %1...</translation>
    
YES  
The translation "დახურულია %1..." means "%1 is closed...", which is incorrect for the English source "%1 is shutting down…". The correct translation should convey the process of shutting down, not just that it is closed. Also, the ellipsis should be the proper Unicode character (…) instead of three dots, matching the source.

Correct translation:  
%1 იხურება…
```

```
        <source>Progress increase per hour</source>
        <translation>პროგრესი გაუმჯობესდება ერთ საათში</translation>
    
YES  
The translation means "Progress will improve in one hour," which adds a future tense and implies an event happening "in" one hour, rather than indicating a rate or amount of progress increase "per hour" as in the source. The source phrase "Progress increase per hour" is a noun phrase indicating a measure or rate, not a prediction.  

Correct translation:  
პროგრესის ზრდა ერთ საათში
```

```
        <source>Reset Options</source>
        <translation>დაბრუნების ოპციები</translation>
    
YES  
The Georgian translation "დაბრუნების ოპციები" literally means "return options" or "options of returning," which is not an accurate translation for "Reset Options" in the Bitcoin or software context. The word "Reset" here implies restoring options to their default or original state, which should be translated with the Georgian term for "reset" or "revert to original settings."

A more appropriate translation would be:  
"აპლიკაციის პარამეტრების მიმართვა" (literally "resetting application settings") or simply  
"პარამეტრების გამეორება" or  
"პარამეტრების გადაყარება", although the most common usage in software is "გადატვირთვის პარამეტრები" or "პარამეტრების გამორთვა" is incorrect.

The best and commonly used Georgian translation for "Reset Options" is:  
"აირჩიე პარამეტრების დაწყება პირვანდლიდან" (literal and long) or more usable is:  
"პარამეტრების გადაყენება" (reset/reinitialize settings).

Suggested correction:  
<translation>პარამეტრების გადაყენება</translation>
```

```
        <source>Choose the default subdivision unit to show in the interface and when sending coins.</source>
        <translation>აირჩიეთ გასაგზავნი თანხის ნაგულისხმევი ერთეული.</translation>
    
YES  
The translation is incomplete and loses information from the original. The source mentions choosing the default subdivision unit for displaying in the interface and when sending coins, but the translation only says "Choose the default unit of amount to be sent," omitting the aspect of showing it in the interface and the idea of "subdivision unit."

A more accurate translation would be:  
"აირჩიეთ ნაგულისხმევი ქვედანაყოფის ერთეული მომხმარებლის ინტერფეისსა და მონეტების გაგზავნის დროს."
```

```
        <source>This change would require a client restart.</source>
        <translation>ამ ცვლილებების ძალაში შესასვლელად საჭიროა კლიენტის დახურვა და ხელახალი გაშვება.</translation>
    
YES  
The original English sentence states: "This change would require a client restart."  
The translation says: "ამ ცვლილებების ძალაში შესასვლელად საჭიროა კლიენტის დახურვა და ხელახალი გაშვება." which translates back to English as: "For these changes to take effect, it is necessary to close and restart the client."  

Problems:  
- The source mentions "This change" (singular), but the translation uses "ამ ცვლილებების" which is plural ("these changes"). This is inconsistent.  
- The original says "restart," but the translation renders it as "close and restart," which is more verbose but not necessarily wrong.  
- Suggest a more literal and singular form aligned with the source.  

Correct translation:  
"ამ ცვლილების გამოსაყენებლად საჭიროა კლიენტის ხელახალი გაშვება."  
(Literally: "To apply this change, a client restart is required.")  

Alternatively, to retain "restart" explicitly:  
"ამ ცვლილებას კლიენტის ხელახალი გაშვება სჭირდება."  

Both are valid, depending on style. The key is to make it singular "change" and keep it concise.  

Therefore:  
YES  
The translation incorrectly uses plural for "change," which should be singular. The phrase is longer than necessary and slightly changes nuance.  

Correct translation:  
"ამ ცვლილების გამოსაყენებლად საჭიროა კლიენტის ხელახალი გაშვება."
```

```
        <source>Mined balance that has not yet matured</source>
        <translation>მოპოვებული თანხა, რომელიც ჯერ არ არის მზადყოფნაში</translation>
    
YES  
The phrase "ჯერ არ არის მზადყოფნაში" is awkward and incorrect in Georgian. The English phrase "Mined balance that has not yet matured" refers to mined Bitcoins whose maturity time period has not yet passed. The correct Georgian translation should convey the idea of the mined amount that is not yet "mature" or "available."

Correct translation:  
მოპოვებული ოდენობა, რომელიც ჯერ არ არის შეწიფული
```

```
        <source>Cannot start bitcoin: click-to-pay handler</source>
        <translation>ვერ გაიშვა bitcoin: click-to-pay</translation>
    
YES  
The translation is incomplete and does not fully convey the source meaning. The original English states "Cannot start bitcoin: click-to-pay handler," meaning the click-to-pay handler for Bitcoin cannot be started. The translation only says "ვერ გაიშვა bitcoin: click-to-pay," which omits "handler" and leaves "click-to-pay" untranslated, which is not ideal for clarity.

Correct translation:  
ვერ გაიშვება bitcoin-ის click-to-pay დამტვირთავი (handler)
```

```
        <source>Peer</source>
        <extracomment>Title of Peers Table column which contains a unique number used to identify a connection.</extracomment>
        <translation>თანაბარი</translation>
    
YES  
The translation "თანაბარი" means "equal" or "peer" in the sense of equality, but in the Bitcoin / P2P networking context, "Peer" refers to a network node or participant, not the concept of equality. A more accurate Georgian translation in this technical context is "პირი" or "გაწონასწორებული" is not appropriate here. The commonly accepted term is "პირი" (meaning "peer" as a participant) or "თანამონაწილე".  

Correct translation:  
პირი
```

```
        <source>Open</source>
        <translation>შექმნა</translation>
    
YES  
The English word "Open" here typically means to open something, such as a file or a dialog, and should be translated accordingly. The Georgian translation "შექმნა" means "Create," which is incorrect.

Correct translation:  
გაფართოვება or გახსნა (depending on context, but generally "გახსნა" is used for "Open")
```

```
        <source>Copy label</source>
        <translation>კოპირება ჭდე</translation>
    
YES  
The Georgian word "ჭდე" means "knot" or "bundle," which is incorrect for translating "label" in this context. The proper word for "label" (as used in Bitcoin wallet labels) is "ნიშანი" or more commonly "ლეგენდა" or simply "ლაბელა" (a transliteration). A suitable translation would be:  

კოპირება ლეიბელის or კოპირება ნიშნის  

Correct translation:  
კოპირება ლეიბელის
```

```
        <source>Verify</source>
        <translation>შემოწმება </translation>
    
YES  
There is an extra trailing whitespace character after the word "შემოწმება" in the translation. This is a formatting issue.

Correct translation:  
შემოწმება
```

```
        <source>Request payment to %1</source>
        <translation>%1-ის გადაზდის მოთხოვნა</translation>
    
YES  
The Georgian translation "%1-ის გადაზდის მოთხოვნა" incorrectly uses "გადაზდის" which means "transfer" rather than "payment." The source text requests a payment to %1, so the correct term should be "გადახდის" (payment).  

Correct translation:  
%1-ის გადახდის მოთხოვნა
```

```
        <source>After Fee:</source>
        <translation>დამატებითი საკომისიო:</translation>
    
YES  
The English phrase "After Fee:" indicates an amount or value remaining after subtracting a fee. The provided Georgian translation "დამატებითი საკომისიო:" means "Additional fee:", which changes the meaning significantly. A more accurate translation preserving the original meaning would be:

საკომისიოს შემდეგ:
```

```
        <source>Custom change address</source>
        <translation>ხურდის მისამართი</translation>
    
YES
The translation "ხურდის მისამართი" literally means "change address" but omits the adjective "custom" (which is "სივრცული" or "მორგებული" in Georgian depending on context). Since "Custom change address" refers to a specific option to designate a user-defined change address in Bitcoin, the adjective must be included.

Correct translation:
მორგებული ხურდის მისამართი
```

```
        <source>Transaction Fee:</source>
        <translation>ტრანსაქციის საფასური - საკომისიო:</translation>
    
YES  
The translation uses a hyphen ("-") which is not present in the source text. The source is simply "Transaction Fee:", so the translation should not add extra punctuation or words like "საკომისიო" unless it is part of the intended meaning. The phrase "ტრანსაქციის საფასური" alone correctly translates "Transaction Fee". Adding "საკომისიო" (meaning "commission" or "fee") is somewhat redundant but could be acceptable if typically used in context, however, the dash in the middle is incorrect formatting.

Correct translation:  
ტრანსაქციის საფასური:
```

```
        <source>Copy after fee</source>
        <translation>დამატებითი საკომისიოს კოპირება</translation>
    
YES  
The translation "დამატებითი საკომისიოს კოპირება" literally means "Copy of the additional fee," which does not accurately represent the English phrase "Copy after fee." In the Bitcoin context, "Copy after fee" likely means copying the amount or value after deducting the fee, or referring to the amount remaining after the fee. The Georgian translation should reflect that the copying is done of the value "after the fee" and not copying the fee itself.

A better translation would be:  
"საკომისიოდან შემდგომი კოპირება"  
or  
"ფულის გადახდის შემდეგ კოპირება" (Copying after payment of the fee)

Depending on the most concise and common terminology in the context, the first is preferred.

Correct translation:  
<translation>საკომისიოდან შემდგომი კოპირება</translation>
```

```
        <source>You can increase the fee later (signals Replace-By-Fee, BIP-125).</source>
        <translation>საკომისიო [fee] შეგიძლიათ შცვალოთ მოგვიანებით (სიგნალები Replace-By-Fee, BIP-125}.
 </translation>
    
YES  
The translation contains a typo and incorrect punctuation: the word "შცვალოთ" should be "შეცვალოთ", and the closing parenthesis is replaced by a closing curly brace "}". Also, the English word "fee" is unnecessarily kept in square brackets and untranslated. It is preferable to either translate or omit the brackets and translate the word properly. The original sentence refers to a fee, so using the Georgian term for "fee" or "საკომისიო" is correct; the brackets around [fee] are unnecessary and inconsistent.

Correct translation:  
საკომისიოს შეგიძლიათ შეცვალოთ მოგვიანებით (სიგნალები Replace-By-Fee, BIP-125).
```

```
        <source>A message that was attached to the bitcoin: URI which will be stored with the transaction for your reference. Note: This message will not be sent over the Bitcoin network.</source>
        <translation>მესიჯი, რომელიც თან ერთვის მონეტებს:  URI, რომელიც შეინახება ტრანსაქციასთან ერთად თქვენთვის. შენიშვნა: მესიჯი არ გაყვება გადახდას ბითქოინის ქსელში.</translation>
    
YES  
The translation contains a few issues:  
- "მონეტებს:" (coins) is incorrect instead of "bitcoin:". The source mentions "bitcoin: URI", which should be translated literally or transliterated as "bitcoin:" rather than replacing bitcoin with "monetebi" (coins).  
- There is an extra space before "URI" ("მონეტებს:  URI")—double space.  
- The phrase "გაყვა" (to accompany) is used incorrectly in the phrase "მესიჯი არ გაყვება გადახდას"; instead "მესიჯი არ გადაიგზავნება" or "არ იგზავნება" (will not be sent) would be more natural and accurate.  
- "გადახდა" (payment) is used instead of "ტრანსაქცია" (transaction), but the source says "Bitcoin network" not "payment". Better: "ბითქოინის ქსელში" is correct for "Bitcoin network". The issue is "გაყვა გადახდას" is grammatically odd and semantically inaccurate, as the message is not sent over the network, not that it is not accompanied by a payment.  

Corrected translation:  
მესიჯი, რომელიც თან ერთვის bitcoin: URI-ს და შეინახება ტრანსაქციასთან ერთად თქვენს ცნობაში. შენიშვნა: ეს მესიჯი არ გადაეცემა ბითქოინის ქსელზე.

(Note: Some Georgian translators prefer "გადაეცემა" over "ან იგზავნება" to express "sent over" a network.)
```

```
        <source>press q to shutdown</source>
        <translation>დახურვა 'q'</translation>
    
YES  
The translation "დახურვა 'q'" literally means "close 'q'" and does not accurately convey the instruction to "press q to shutdown." The verb "press" is missing and should be explicitly stated to guide the user correctly.  

Correct translation:  
'q' დაჭირეთ დასახურად  
(or more formally)  
'დაჭირეთ q-ღილაკს დასახურად'
```

```
        <source>Inputs</source>
        <translation>ხარჯები</translation>
    
YES  
The Georgian translation "ხარჯები" means "expenses" or "costs," which is incorrect in the Bitcoin context. Here, "Inputs" refers to transaction inputs, not expenses. A more accurate translation for "Inputs" in the Bitcoin context would be "შეყვანები" or "ინპუტები" (the former is more formal and native).  

Correct translation:  
შეყვანები
```

```
        <source>Confirming (%1 of %2 recommended confirmations)</source>
        <translation>დადასტურებულია (%1,  რეკომენდებულია %2)</translation>
    
YES  
The translation does not accurately convey the meaning of "Confirming (%1 of %2 recommended confirmations)". The original message indicates a process is ongoing, with a partial count of confirmations out of a recommended total. The translated version states "confirmed" (დადასტურებულია), which implies completion rather than an ongoing process, and the structure does not clearly express the fraction of confirmations.

A better translation would be:  
დადასტურების პროცესში (%1 מתוך რეკომენდებული %2 დადასტურებისა)
```

```
        <source>Confirmed (%1 confirmations)</source>
        <translation>დადასტურებულია (%1დასტური)</translation>
    
YES  
There is a missing space between the number placeholder %1 and the word "დასტური". In Georgian, a space is generally required between the number and the noun. Also, the word "დასტური" should be plural ("დასტურები") to match the English plural "confirmations."

Correct translation:  
დადასტურებულია (%1 დასტურები)
```

```
        <source>Copy label</source>
        <translation>კოპირება ჭდე</translation>
    
YES  
The Georgian word "ჭდე" means "knot" or "bundle," which is incorrect for translating "label" in this context. The proper word for "label" (as used in Bitcoin wallet labels) is "ნიშანი" or more commonly "ლეგენდა" or simply "ლაბელა" (a transliteration). A suitable translation would be:  

კოპირება ლეიბელის or კოპირება ნიშნის  

Correct translation:  
კოპირება ლეიბელის
```

```
        <source>Copy transaction ID</source>
        <translation>ტრანზაქციის დაკოპირება ID</translation>
    
YES  
The translation mixes Georgian and English unnaturally. "ID" should be translated or transliterated consistently with Georgian usage. A better translation would be:  
"ტრანზაქციის ID-ის დაკოპირება"  
This correctly reflects "Copy transaction ID" in fluent Georgian.
```

```
        <source>Copy full transaction details</source>
        <translation>სრული ტრანზაქციის კოპირება დეტალები</translation>
    
YES  
The Georgian translation word order is incorrect and sounds unnatural. "დეტალები" (details) should precede "კოპირება" (copying) as an object, and "სრული ტრანზაქციის" (full transaction's) should directly modify "დეტალები." The correct phrasing is "კოპირება სრული ტრანზაქციის დეტალების," so the intended meaning "Copy full transaction details" is conveyed properly.

Correct translation:  
კოპირება სრული ტრანზაქციის დეტალების
```

```
        <source>Increase transaction fee</source>
        <translation>ტრანზაქციის გაზრდა საფასური</translation>
    
YES
The Georgian translation has incorrect word order and grammatical construction. The phrase should properly convey "Increase transaction fee" meaning "Increase the fee of the transaction" with the correct structure and case endings.

Correct translation:
ტრანზაქციის საფარის გაზრდა
```

```
        <source>Error creating %s</source>
        <translation>შეცდომა%s-ის შექმნისას</translation>
    
YES
There is a missing space between "შეცდომა" and "%s-ის". They should be separated by a space for proper formatting.

Correct translation:
შეცდომა %s-ის შექმნისას
```

```
        <source>Error opening block database</source>
        <translation>ბლოკთა ბაზის შექმნა ვერ მოხერხდა</translation>
    
YES  
The English source "Error opening block database" indicates a problem occurred while opening the existing block database, not when creating it. The Georgian translation "ბლოკთა ბაზის შექმნა ვერ მოხერხდა" means "Creation of block database failed," which implies the error occurred during creation rather than opening. This changes the meaning and could confuse users.

Correct translation:  
ბლოკთა მონაცემთა ბაზის გახსნა ვერ მოხერხდა
```

```
        <source>Transaction amount too small</source>
        <translation>ტრანსაქციების რაოდენობა ძალიან ცოტაა</translation>
    
YES  
The translation "ტრანსაქციების რაოდენობა ძალიან ცოტაა" means "The number of transactions is too small," which does not accurately convey the original meaning of "Transaction amount too small." The correct translation should reflect the amount (sum of money), not the number (quantity) of transactions.

Correct translation:  
ტრანზაქციის თანხა ძალიან პატარაა
```
</details>
