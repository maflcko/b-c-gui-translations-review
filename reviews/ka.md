# Translations Review by LLM (✨ experimental)

The review quality depends on the LLM and the language. Currently, a fast LLM without rate limits is used. If you are interested in better quality for a specific language, please file an issue to ask for it to be re-run with a stronger model.



<details><summary>ka</summary>

[If the result is of low quality, please file an issue to find a better LLM for this language.](../../issues/new?title=%5Bka%5D%20low%20quality)


```
        <source>Passphrase Dialog</source>
        <translation>საიდუმლო ფრაზის მიმოცვლა</translation>
    
YES
The translation "საიდუმლო ფრაზის მიმოცვლა" is inaccurate. "მიმოცვლა" means "exchange", but "dialog" here refers to a "window" or "dialog box" in software UI terms, not an exchange. The word "დიალოგი" is commonly used for "dialog" in software Georgian translations.

Correct translation:
საიდუმლო ფრაზის დიალოგი
```

```
        <source>Enter the new passphrase for the wallet.&lt;br/&gt;Please use a passphrase of &lt;b&gt;ten or more random characters&lt;/b&gt;, or &lt;b&gt;eight or more words&lt;/b&gt;.</source>
        <translation>შეიყვანეთ საფულის ახალი საიდუმლო ფრაზა .1 გამოიყენეთ მე –2 ან მეტი შემთხვევითი სიმბოლოების 2 ან 3 – ზე მეტი რვა ან მეტი სიტყვის პაროლი 3.</translation>
    
YES
The translation is incorrect and contains errors. It has inserted numbers (1, 2, 3) instead of properly translating the structure about the passphrase requirements. The meaning is lost, and the style is not natural Georgian.

Correct translation:
გთხოვთ, შეიყვანოთ საფულის ახალი საიდუმლო ფრაზა.&lt;br/&gt; გამოიყენეთ &lt;b&gt;ათი ან მეტი შემთხვევითი სიმბოლო&lt;/b&gt; ან &lt;b&gt;რვა ან მეტი სიტყვა&lt;/b&gt; თქვენი ფრაზისთვის.
```

```
        <source>Remember that encrypting your wallet cannot fully protect your bitcoins from being stolen by malware infecting your computer.</source>
        <translation>გახსოვდეთ, რომ თქვენი საფულის დაშიფვრა ვერ უზრუნველყოფს სრულად დაიცვას თქვენი ბიტკოინების მოპარვა კომპიუტერში მავნე პროგრამებით.</translation>
    
YES
The translation has some grammatical issues and the meaning is distorted. Specifically, "ვერ უზრუნველყოფს სრულად დაიცვას თქვენი ბიტკოინების მოპარვა კომპიუტერში მავნე პროგრამებით" is awkward and incorrect. It should convey that encryption cannot completely prevent theft by malware on your computer.

Correct translation:
გახსოვდეთ, რომ საფულის დაშიფვრა ვერ სრულად დაიცავს თქვენს ბიტკოინებს კომპიუტერში მავნე პროგრამების მიერ ქურდობისგან.
```

```
        <source>Wallet to be encrypted</source>
        <translation>დაშიფრულია საფულე</translation>
    
YES
The translation means "The wallet is encrypted" instead of "Wallet to be encrypted". This changes the meaning from a future/pending action to a completed one.

Correct translation:
საფულე დასაშიფრია
```

```
        <source>Your wallet is about to be encrypted. </source>
        <translation>თქვენი საფულე იშიფრება</translation>
    
YES
The Georgian translation is inaccurate and changes the meaning. The source says the wallet "is about to be encrypted" (future/impending action), but the translation "თქვენი საფულე იშიფრება" means "Your wallet is being encrypted" (present tense, ongoing action). The translation also omits the final period.

Correct translation:
თქვენი საფულე მალე დაიშიფრება.
```

```
        <source>Banned Until</source>
        <translation>სანამ აიკრძალა</translation>
    
YES  
The translation "სანამ აიკრძალა" is incorrect; it means "until (it) was banned," which does not convey the intended meaning of "Banned Until" (i.e., the time up to which the ban lasts). The correct translation would be:  
"აკრძალულია დღემდე" or "აკრძალულია სანამ" or, more naturally, "აკრძალული დღეამდე".

Correct translation:  
აკრძალულია დღემდე
```

```
        <source>Minimize</source>
        <translation>ჩახურვა</translation>
    
YES
The translation "ჩახურვა" actually means "Close" in Georgian, not "Minimize." The correct translation for "Minimize" is "მინიმალიზაცია" or more commonly "ჩაკეცვა".

Correct translation:
ჩაკეცვა
```

```
        <source>Sign message…</source>
        <translation>ხელმოწერა შეტყობინება…</translation>
    
YES
The Georgian translation has incorrect word order and case. The verb "ხელმოწერა" ("signature" or "to sign") should come after the object with the appropriate postposition. The more natural translation would be:

Correct translation:
შეტყობინებაზე ხელმოწერა…
```

```
        <source>Click for more actions.</source>
        <extracomment>A substring of the tooltip. "More actions" are available via the context menu.</extracomment>
        <translation>მეტი...</translation>
    
YES
The translation "მეტი..." means "more...", which is incomplete and does not convey the idea of "Click for more actions." It loses context and instruction from the source.

Correct translation:
დააწკაპუნეთ მეტი ქმედებების სანახავად.
```

```
        <source>Sent transaction</source>
        <translation>გაგზავნილი ტრანსაქციები</translation>
    
YES
The translation uses the plural form "გაგზავნილი ტრანსაქციები" ("Sent transactions") instead of the singular "Sent transaction". This is an error as the source is singular.

Correct translation:
გაგზავნილი ტრანსაქცია
```

```
        <source>Coin Selection</source>
        <translation>Coin-ები</translation>
    
YES
The translation "Coin-ები" simply pluralizes the English word "Coin" using a Georgian suffix, which does not accurately reflect the meaning of "Coin Selection" (the process of choosing coins/UTXOs for a transaction). It also omits the term "Selection".

Correct translation:
მონეტების არჩევა
```

```
        <source>After Fee:</source>
        <translation>დამატებითი საკომისიო:</translation>
    
YES
The translation is inaccurate. The English "After Fee:" means "the amount after subtracting the fee," while the Georgian translation "დამატებითი საკომისიო:" means "additional fee," which is incorrect.

Correct translation:
საკომისიოს შემდეგ:
```

```
        <source>Copy transaction ID and output index</source>
        <translation>ტრანზაქციის კოპირება ID და ინდექსის გამოტანა</translation>
    
YES
The translation is inaccurate and awkward in Georgian. It says "კოპირება" (copying) of the transaction, then "ID and index output", which is not natural or correct. Also, the structure does not match the source.

Correct translation:
ტრანზაქციის ID-ისა და გამოშვების ინდექსის კოპირება
```

```
        <source>Copy after fee</source>
        <translation>დამატებითი საკომისიოს კოპირება</translation>
    
YES
The translation is inaccurate. The English "Copy after fee" (likely referring to copying the amount *after* subtracting the fee) is translated as "დამატებითი საკომისიოს კოპირება", which means "Copy additional fee," not the original intent.

Correct translation:
საკომისიოს გამოკლების შემდეგ კოპირება
```

```
        <source>Are you sure you wish to close the wallet &lt;i&gt;%1&lt;/i&gt;?</source>
        <translation>დაიხუროს საფულე&lt;i&gt;%1&lt;/i&gt; ?</translation>
    
YES
The translation is not accurate. The source asks "Are you sure you wish to close the wallet...?", but the Georgian translation uses an imperative "დაიხუროს", which means "Let the wallet be closed", and does not capture the question or certainty aspect. There is also a space before the question mark that should not be there.

Correct translation:
დარწმუნებული ხართ, რომ გსურთ საფულე &lt;i&gt;%1&lt;/i&gt; დახურვა?
```

```
        <source>Encrypt Wallet</source>
        <translation>საფულის დაცვა [Encrypt Wallet]</translation>
    
YES
The translation is partially problematic. While "საფულის დაცვა" means "Wallet protection," it does not directly convey "Encrypt Wallet." The inclusion of "[Encrypt Wallet]" in brackets is unnecessary and not a proper translation. The text should directly translate "Encrypt Wallet" as "საფულის დაშიფვრა".

Correct translation:
საფულის დაშიფვრა
```

```
        <source>Create</source>
        <translation>ახალი</translation>
    
YES
The translation "ახალი" means "new" in Georgian, not "Create". The correct translation for "Create" is "შექმნა" or "შექმენით" (imperative/formal).

Correct translation:
შექმნა (or შექმენით, depending on context)
```

```
        <source>Error: Specified data directory "%1" cannot be created.</source>
        <translation>შეცდომა: მითითებულ მონაცემთა დირექტორია „%1“ არ არის შექმნილი.</translation>
    
YES
The translation has an inaccuracy. The English source says "cannot be created," which means the directory could not be created (an attempt failed), but the Georgian translation says "არ არის შექმნილი" which means "is not created" (describing its state, not the failed action). The error message should instead indicate the failure to create.

Correct translation:
შეცდომა: მითითებული მონაცემთა დირექტორიის „%1“ შექმნა შეუძლებელია.
```

```
        <source>%1 is shutting down…</source>
        <translation> დახურულია %1...</translation>
    
YES
There are two issues:  
1. The ellipsis character is not consistent with the source (the source uses a single Unicode ellipsis '…', translation uses three periods '...').
2. The translation reverses word order and omits the verb. Correct Georgian structure would be to clarify that %1 is shutting down, not that it "is closed".

Correct translation:
%1 ითიშება…
```

```
        <source>Progress increase per hour</source>
        <translation>პროგრესი გაუმჯობესდება ერთ საათში</translation>
    
YES
The translation "პროგრესი გაუმჯობესდება ერთ საათში" means "Progress will improve in one hour" rather than "Progress increase per hour," which is about a rate/amount of progress per hour.

Correct translation:
საათში პროგრესის ზრდა
```

```
        <source>Reset Options</source>
        <translation>დაბრუნების ოპციები</translation>
    
YES
The translation "დაბრუნების ოპციები" means "return options" or "options of returning" in Georgian, which does not accurately convey the intent of "Reset Options". The concept of 'reset' in software (to restore defaults or original state) is generally rendered as "გადატვირთვა" (reset/restart) or "საწყისი პარამეტრების დაბრუნება" (restore default options/settings). 

Correct translation:
პარამეტრების განულება

Or a more expanded version that matches UI conventions:
პარამეტრების ყურადღით დაბრუნება Defaults-თან

But typically, "პარამეტრების განულება" is used.
```

```
        <source>Choose the default subdivision unit to show in the interface and when sending coins.</source>
        <translation>აირჩიეთ გასაგზავნი თანხის ნაგულისხმევი ერთეული.</translation>
    
YES
The translation omits part of the original meaning, specifically the part about the interface display. The original refers to both displaying in the interface and sending coins, but the translation only mentions sending.

Correct translation:
აირჩიეთ ნაგულისხმევი დანაყოფის ერთეული, რომელიც გამოჩნდება ინტერფეისში და მონეტების გაგზავნისას.
```

```
        <source>Peer</source>
        <extracomment>Title of Peers Table column which contains a unique number used to identify a connection.</extracomment>
        <translation>თანაბარი</translation>
    
YES
The Georgian word "თანაბარი" means "equal" or "equivalent", not "peer" in the context of networking or Bitcoin peers. In Georgian, "Peer" (as in network peer) is better translated as "თანამონაწილე", "პირი", or "პირი (ქსელში)". The most accurate and context-appropriate term is "თანამონაწილე" or simply "პირი".

Correct translation:
თანამონაწილე
```

```
        <source>Open</source>
        <translation>შექმნა</translation>
    
YES
The translation is incorrect. The English word "Open" was translated as "შექმნა", which means "Create" in Georgian.

Correct translation:
გახსნა
```

```
        <source>Request payment to %1</source>
        <translation>%1-ის გადაზდის მოთხოვნა</translation>
    
YES
The translation "%1-ის გადაზდის მოთხოვნა" is problematic. The word "გადაზდის" means "transfer" or "remittance," which is a less precise translation for "payment." Additionally, the construction is somewhat unnatural in Georgian for this context.

A more accurate and natural translation would be:
"%1-თვის გადახდის მოთხოვნა"

Correct translation:
%1-თვის გადახდის მოთხოვნა
```

```
        <source>After Fee:</source>
        <translation>დამატებითი საკომისიო:</translation>
    
YES
The translation is inaccurate. The English "After Fee:" means "the amount after subtracting the fee," while the Georgian translation "დამატებითი საკომისიო:" means "additional fee," which is incorrect.

Correct translation:
საკომისიოს შემდეგ:
```

```
        <source>Custom change address</source>
        <translation>ხურდის მისამართი</translation>
    
YES
The translation "ხურდის მისამართი" means "change address" but omits "custom" ("საკუთარი" or "მორგებული") from the phrase, which is important to indicate the user-set aspect in the Bitcoin context.

Correct translation:
მორგებული ხურდის მისამართი
```

```
        <source>Transaction Fee:</source>
        <translation>ტრანსაქციის საფასური - საკომისიო:</translation>
    
YES
The translation "ტრანსაქციის საფასური - საკომისიო:" introduces redundancy by adding "საკომისიო" (which also means "fee" or "commission") in addition to "ტრანსაქციის საფასური" ("transaction fee"). This is unnecessarily repetitive and diverges from the concise original. The correct translation should simply be:

Correct translation:
ტრანსაქციის საფასური:
```

```
        <source>Copy after fee</source>
        <translation>დამატებითი საკომისიოს კოპირება</translation>
    
YES
The translation is inaccurate. The English "Copy after fee" (likely referring to copying the amount *after* subtracting the fee) is translated as "დამატებითი საკომისიოს კოპირება", which means "Copy additional fee," not the original intent.

Correct translation:
საკომისიოს გამოკლების შემდეგ კოპირება
```

```
        <source>You can increase the fee later (signals Replace-By-Fee, BIP-125).</source>
        <translation>საკომისიო [fee] შეგიძლიათ შცვალოთ მოგვიანებით (სიგნალები Replace-By-Fee, BIP-125}.
 </translation>
    
YES
There are several issues:
1. The Georgian word "შცვალოთ" is misspelled, should be "შეცვალოთ".
2. "[fee]" is not part of the original and should not be inserted; "საკომისიო" alone is fine.
3. The translation uses a wrong closing bracket (curly bracket instead of parenthesis).
4. Unwanted whitespace at the end of the translation.

Correct translation:
საკომისიო შეგიძლიათ შეცვალოთ მოგვიანებით (შეტყობინება Replace-By-Fee, BIP-125).
```

```
        <source>A message that was attached to the bitcoin: URI which will be stored with the transaction for your reference. Note: This message will not be sent over the Bitcoin network.</source>
        <translation>მესიჯი, რომელიც თან ერთვის მონეტებს:  URI, რომელიც შეინახება ტრანსაქციასთან ერთად თქვენთვის. შენიშვნა: მესიჯი არ გაყვება გადახდას ბითქოინის ქსელში.</translation>
    
YES
There are a few issues:
- "მონეტებს:" should be "bitcoin:" to faithfully translate the URI scheme.
- The translation omits "for your reference" nuance.
- "მესიჯი არ გაყვება გადახდას ბითქოინის ქსელში." does not explicitly state "message will not be sent over the Bitcoin network" but instead says "the message will not follow the payment" which is less precise.
- Double space after ":" in "მონეტებს:  URI".

Correct translation:
შეტყობინება, რომელიც თან ერთვის bitcoin: URI-ს და შეინახება ტრანსაქციასთან ერთად თქვენი მითითებისთვის. შენიშვნა: ეს შეტყობინება ბიტკოინის ქსელში არ გადაიგზავნება.
```

```
        <source>press q to shutdown</source>
        <translation>დახურვა 'q'</translation>
    
YES
The Georgian translation is not accurate. It translates as "close 'q'", which does not clearly instruct the user to "press q" in order to shut down.

Correct translation:
დააჭირეთ q-ს დასახურად
```

```
        <source>Inputs</source>
        <translation>ხარჯები</translation>
    
YES
The translation of "Inputs" as "ხარჯები" is incorrect. "ხარჯები" means "expenses" or "expenditures," not "inputs" in the context of Bitcoin transactions. The correct translation for "Inputs" in this context would be "შეყვანები" or "ინპუტები".

Correct translation:
შეყვანები
```

```
        <source>Confirming (%1 of %2 recommended confirmations)</source>
        <translation>დადასტურებულია (%1,  რეკომენდებულია %2)</translation>
    
YES
The translation does not accurately convey the progressive aspect ("Confirming") and misplaces the confirmation count. The source means that the confirmation is in progress ("Confirming"), showing how many confirmations have happened out of the recommended total.

Correct translation:
დადასტურება მიმდინარეობს (%1 შესაძლებელია %2 რეკომენდებული დადასტურებიდან)
```

```
        <source>Confirmed (%1 confirmations)</source>
        <translation>დადასტურებულია (%1დასტური)</translation>
    
YES
The translation is inaccurate. "%1დასტური" means "%1 confirmation" (singular), but the source says "confirmations" (plural), and the translation omits the word "დადასტურება" or "დადასტურება(ები)" for clarification. Also, there is a missing space after %1. The correct Georgian translation should be:

დადასტურებულია (%1 დადასტურება)

Or, to match plural more naturally:

დადასტურებულია (%1 დადასტურება/დადასტურება(ები))

But most commonly:

დადასტურებულია (%1 დადასტურება)
```

```
        <source>Copy transaction ID</source>
        <translation>ტრანზაქციის დაკოპირება ID</translation>
    
YES
The translation is not idiomatic. The phrase "ტრანზაქციის დაკოპირება ID" is awkward and incorrect in word order; a proper translation would place "ID" before "დაკოპირება". A better, idiomatic translation is:

Correct translation:
ტრანზაქციის ID-ის დაკოპირება
```

```
        <source>Copy full transaction details</source>
        <translation>სრული ტრანზაქციის კოპირება დეტალები</translation>
    
YES
The translation is grammatically incorrect. It translates to "Copy transaction details full" or "Full transaction's copying details", which is not natural in Georgian. The correct Georgian translation should have the structure: "დაკოპირება სრული ტრანზაქციის დეტალების" or "დაკოპირეთ სრული ტრანზაქციის დეტალები".

Correct translation:
სრული ტრანზაქციის დეტალების დაკოპირება
or
დააკოპირეთ სრული ტრანზაქციის დეტალები
```

```
        <source>Increase transaction fee</source>
        <translation>ტრანზაქციის გაზრდა საფასური</translation>
    
YES
The word order in the Georgian translation is incorrect—the phrase "ტრანზაქციის გაზრდა საფასური" literally reads as "transaction's increase fee," which is not proper Georgian syntax. The correct translation should be: 

ტრანზაქციის საფასურის გაზრდა

This directly translates back as "increase of transaction fee," matching the source meaning and proper Georgian grammar.
```

```
        <source>Error creating %s</source>
        <translation>შეცდომა%s-ის შექმნისას</translation>
    
YES
There is a formatting issue: there is no space between the word "შეცდომა" (Error) and the format specifier "%s". In Georgian, a space should be present for clarity.

Correct translation:
შეცდომა %s-ის შექმნისას
```

```
        <source>Error opening block database</source>
        <translation>ბლოკთა ბაზის შექმნა ვერ მოხერხდა</translation>
    
YES
The translation "ბლოკთა ბაზის შექმნა ვერ მოხერხდა" means "Failed to create block database", which differs from the source "Error opening block database". The source refers to an error in opening (not creating) the database.

Correct translation:
ბლოკთა ბაზის გახსნის შეცდომა
```

```
        <source>Transaction amount too small</source>
        <translation>ტრანსაქციების რაოდენობა ძალიან ცოტაა</translation>
    
YES
The translation is incorrect. The original English text "Transaction amount too small" refers to the amount (value) of the transaction, not the number of transactions. The current translation says, "The number of transactions is too small," which is inaccurate.

Correct translation:
ტრანსაქციის თანხა ძალიან მცირეა
```
</details>

Number of issues: 41.
