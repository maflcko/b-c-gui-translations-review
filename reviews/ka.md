# Translations Review by LLM (✨ experimental)

The review quality depends on the LLM and the language. Currently, a fast LLM without rate limits is used. If you are interested in better quality for a specific language, please file an issue to ask for it to be re-run with a stronger model.



<details><summary>ka</summary>

[If the result is of low quality, please file an issue to find a better LLM for this language.](../../issues/new?title=%5Bka%5D%20low%20quality)


```
        <source>Enter address or label to search</source>
        <translation> მოსაძებნად შეიყვანეთ მისამართი ან მოსანიშნი</translation>
    
YES - The translation includes an unnecessary space at the beginning of the string. The correct translation is: "მოსაძებნად შეიყვანეთ მისამართი ან მოსანიშნი"
```

```
        <source>Passphrase Dialog</source>
        <translation>საიდუმლო ფრაზის მიმოცვლა</translation>
    
YES: The translation uses "მიმოცვლა" (mimot'svla) which means "exchange" or "circulation". In the context of a Bitcoin passphrase, this is incorrect. The correct term should refer to a dialog box or window for entering a passphrase. The word "dialog" is not directly translated.

Correct translation: საიდუმლო ფრაზის ფანჯარა (saidumlo frazis panjara) or საიდუმლო ფრაზის დიალოგი (saidumlo frazis dialogi). The latter is a direct transliteration and might be understood. Given the context, a more descriptive term for a window or dialog box is preferable. Let's use "ფანჯარა" (window).

Correct translation: საიდუმლო ფრაზის ფანჯარა
```

```
        <source>Enter the new passphrase for the wallet.&lt;br/&gt;Please use a passphrase of &lt;b&gt;ten or more random characters&lt;/b&gt;, or &lt;b&gt;eight or more words&lt;/b&gt;.</source>
        <translation>შეიყვანეთ საფულის ახალი საიდუმლო ფრაზა .1 გამოიყენეთ მე –2 ან მეტი შემთხვევითი სიმბოლოების 2 ან 3 – ზე მეტი რვა ან მეტი სიტყვის პაროლი 3.</translation>
    
YES. The translation is largely garbled and contains nonsensical sequences of numbers and symbols. The original formatting and intent are lost.

Correct translation: შემოიყვანეთ საფულის ახალი პაროლი. გთხოვთ, გამოიყენოთ 10 ან მეტი შემთხვევითი სიმბოლოსგან ან 8 ან მეტი სიტყვისგან შემდგარი პაროლი.
```

```
        <source>Remember that encrypting your wallet cannot fully protect your bitcoins from being stolen by malware infecting your computer.</source>
        <translation>გახსოვდეთ, რომ თქვენი საფულის დაშიფვრა ვერ უზრუნველყოფს სრულად დაიცვას თქვენი ბიტკოინების მოპარვა კომპიუტერში მავნე პროგრამებით.</translation>
    
YES, The Georgian translation is grammatically incorrect and sounds unnatural. The phrase "cannot fully protect your bitcoins from being stolen by malware infecting your computer" is not accurately conveyed.

Correct translation: გახსოვდეთ, რომ თქვენი საფულის დაშიფვრა სრულად ვერ დაიცავს თქვენს ბიტკოინებს კომპიუტერში არსებული მავნე პროგრამებით მოპარვისგან.
```

```
        <source>Wallet to be encrypted</source>
        <translation>დაშიფრულია საფულე</translation>
    
YES
The Georgian translation provided is "დაშიფრულია საფულე", which means "The wallet has been encrypted" or "Wallet is encrypted".
The source text is "Wallet to be encrypted". This implies a future action or a state of readiness for encryption.
The provided translation uses the perfective verb "დაშიფრულია" (dashifrulia), which indicates a completed action or a state of being already encrypted. This is a mismatch in tense and meaning.

The correct translation should convey the idea of a wallet that is *intended* to be encrypted, or that is *ready* for encryption.

A more accurate translation would be:
"დასაშიფრებელი საფულე" (dasashifrebeli sapule) - This translates to "Wallet to be encrypted" or "Wallet for encryption". The "-ებელი" (-ebeli) suffix in Georgian often indicates something that is to be done or is capable of doing something.

<source>Wallet to be encrypted</source>
<translation>დასაშიფრებელი საფულე</translation>
```

```
        <source>Your wallet is about to be encrypted. </source>
        <translation>თქვენი საფულე იშიფრება</translation>
    
YES
The translation is missing the word "about to" which means the sentence is not accurate. Also, the translation does not include the period at the end of the sentence.

Correct translation: თქვენი საფულე იშიფრება
Correct translation: თქვენი საფულე იშიფრება.
```

```
        <source>The passphrase entered for the wallet decryption was incorrect.</source>
        <translation>საფულის განშიფრვის ფრაზა-პაროლი არაწორია</translation>
    
YES, The translation is problematic because it is missing the "%s" format specifier.
The correct translation is: საფულის განშიფრვის ფრაზა-პაროლი "%s" არაწორია.
```

```
        <source>Banned Until</source>
        <translation>სანამ აიკრძალა</translation>
    
YES, The translation is inaccurate and nonsensical. The correct translation for "Banned Until" in Georgian, in the context of Bitcoin or any other platform, would be "აკრძალულია სანამ" or "დაბლოკილია სანამ".

**Explanation:** The provided translation "სანამ აიკრძალა" literally means "Until it was banned," which is grammatically incorrect and doesn't convey the intended meaning of a future time until which a ban is in effect.

**Correct Translation:** აკრძალულია სანამ
```

```
        <source>Do you want to reset settings to default values, or to abort without making changes?</source>
        <extracomment>Explanatory text shown on startup when the settings file cannot be read. Prompts user to make a choice between resetting or aborting.</extracomment>
        <translation>გსურთ პარამეტრების ხელახლა დაყენება ნაგულისხმევ მნიშვნელობებზე თუ შეწყვეტთ ცვლილებების შეტანის გარეშე?</translation>
    
YES - The translation uses "გსურთ პარამეტრების ხელახლა დაყენება ნაგულისხმევ მნიშვნელობებზე" which translates to "Do you want to reset the settings to default values". This is correct. However, the second part of the sentence "თუ შეწყვეტთ ცვლილებების შეტანის გარეშე?" translates to "or if you stop without making changes?". This is slightly awkward and the word "შეწყვეტთ" (stop/abort) is not the best choice here. A more natural phrasing would be "თუ გააუქმოთ ცვლილებების გარეშე?" which means "or if you cancel without changes?".

Correct translation: გაქვთ თუ არა პარამეტრების ნაგულისხმევ მნიშვნელობებზე აღდგენა, თუ გააუქმოთ ცვლილებების გარეშე?
```

```
        <source>N/A</source>
        <translation>მიუწვდ.</translation>
    
YES, The translation is problematic because it is an incomplete abbreviation of the English word "Not Available" and does not accurately convey the meaning in Georgian. The correct translation for "N/A" in this context would be "არ არის ხელმისაწვდომი".
მიუწვდ.
```

```
        <source>Show information about %1</source>
        <translation>%1-ის შესახებ ინფორმაციის ჩვენება</translation>
    
YES, The translation is problematic because the placeholder %1 is placed at the beginning of the sentence which is not the case in the source sentence.
Correct translation: %1-ის შესახებ ინფორმაციის ჩვენება
```

```
        <source>Modify configuration options for %1</source>
        <translation>%1-ის კონფიგურირების პარამეტრების რედაქტირება</translation>
    
YES. The translation is problematic because it fails to translate the word "configuration". The correct translation should be:

%1-ის კონფიგურაციის პარამეტრების რედაქტირება
```

```
        <source>Minimize</source>
        <translation>ჩახურვა</translation>
    
YES, The translation is incorrect. The English word "Minimize" means to reduce something to the smallest possible amount or degree. The provided Georgian translation "ჩახურვა" (chakhurva) means "to close" or "to shut down." A more accurate translation for "Minimize" in the context of Bitcoin would be "შემცირება" (shemt'sireba).
The correct translation is:
<translation>შემცირება</translation>
```

```
        <source>Change the passphrase used for wallet encryption</source>
        <translation>საფულის დაშიფრვის ფრაზა-პაროლის შეცვლა</translation>
    
YES, the translation is problematic. The English phrase "passphrase used for wallet encryption" is translated as "საფულის დაშიფვრის ფრაზა-პაროლის" which literally means "wallet encryption phrase-password". The hyphen between "phrase" and "password" is not standard in Georgian and creates an awkward phrasing.

A more natural and accurate translation would be:

<source>Change the passphrase used for wallet encryption</source>
<translation>შეცვალეთ საფულის დაშიფვრის პაროლი</translation>
```

```
        <source>Change Passphrase…</source>
        <translation> შეცვალეთ პაროლის ფრაზა…</translation>
    
YES, The Georgian word for "passphrase" is "სიტყვათწყობა" (sit'qvatstqoba) or "სიტყვების ერთობლიობა" (sit'qvebis ert'obl'oba). While "ფრაზა" (p'raza) can mean phrase, it doesn't accurately convey the meaning of "passphrase" in this context. Also, the translation uses "შეცვალეთ" (shets'valet) which is the imperative form of "to change", but the source text uses the gerund "Change" as a verb functioning as a noun, indicating an action. A more appropriate translation for the source text would be "შეცვლა" (shets'vla) or "გამოცვლა" (gamots'vla).

Therefore, a more accurate translation would be:
<translation>შეცვალეთ პაროლის ფრაზა...</translation>
```

```
        <source>Sign message…</source>
        <translation>ხელმოწერა შეტყობინება…</translation>
    
YES
The translation is grammatically incorrect. The verb "to sign" should agree with the noun "message". The correct translation uses the genitive case for "message" before the verb.

Correct translation: შეტყობინების ხელმოწერა…
```

```
        <source>Verify messages to ensure they were signed with specified Bitcoin addresses</source>
        <translation>შეამოწმეთ, რომ მესიჯები ხელმოწერილია მითითებული Bitcoin-მისამართით</translation>
    
YES, The translation is problematic because it uses a singular form of "address" (მისამართით) while the source text uses the plural form "addresses". The correct translation should use the plural form of "address" in Georgian.

Correct translation: შეამოწმეთ, რომ მესიჯები ხელმოწერილია მითითებული Bitcoin-მისამართებით
```

```
        <source>%1 behind</source>
        <translation>%1 გავლილია</translation>
    
YES - The translation is inaccurate. The Georgian word "გავლილია" means "passed" or "completed," which does not convey the meaning of "behind" in this context. The correct translation should indicate something that is behind in terms of progress or a sequence.

Correct translation: %1 ჩამორჩება
```

```
        <source>Click for more actions.</source>
        <extracomment>A substring of the tooltip. "More actions" are available via the context menu.</extracomment>
        <translation>მეტი...</translation>
    
YES - The translation is a single word "მეტი" which means "More". The English source text is "Click for more actions." The provided translation does not convey the full meaning of the source text, specifically missing the action of "clicking" and the concept of "actions." A more accurate translation would be:

"მეტი ქმედებებისთვის დააწკაპუნეთ."
```

```
        <source>Sent transaction</source>
        <translation>გაგზავნილი ტრანსაქციები</translation>
    
YES, The English source text is singular ("transaction"), but the Georgian translation is plural ("ტრანსაქციები" - transactions).
The correct translation should be singular.
გაგზავნილი ტრანსაქცია
```

```
        <source>Wallet is &lt;b&gt;encrypted&lt;/b&gt; and currently &lt;b&gt;locked&lt;/b&gt;</source>
        <translation>საფულე &lt;b&gt;დაშიფრულია&lt;/b&gt; და ამჟამად &lt;b&gt;დაბლოკილია&lt;/b&gt;</translation>
    
UNK_LANG
```

```
        <source>Coin Selection</source>
        <translation>Coin-ები</translation>
    
YES: The translation is too brief and doesn't accurately convey the meaning of "Coin Selection" in the context of Bitcoin. It simply translates to "Coins". The context suggests a process or a method of selecting coins, not just the coins themselves.

Correct translation: მონეტების შერჩევა
```

```
        <source>After Fee:</source>
        <translation>დამატებითი საკომისიო:</translation>
    
YES, The translation is problematic because it does not accurately convey the meaning of "After Fee". In the context of Bitcoin, "After Fee" refers to the amount remaining after a transaction fee has been deducted, not an additional fee.

The correct translation should be:

<translation>გადასახადის შემდეგ:</translation>
```

```
        <source>Copy label</source>
        <translation>კოპირება ჭდე</translation>
    
YES, The translation is problematic. The Georgian word "ჭდე" is not a correct translation for "label" in this context. The correct translation for "label" in the context of Bitcoin or general user interfaces would be "ეტიკეტი" or "სახელწოდება".

Correct translation: დააკოპირეთ ეტიკეტი
```

```
        <source>Copy transaction ID and output index</source>
        <translation>ტრანზაქციის კოპირება ID და ინდექსის გამოტანა</translation>
    
YES, the translation is problematic because it doesn't accurately convey the meaning of the source text. It seems to have misinterpreted "output index" as "print index" or "extract index" and also incorrectly translated "Copy transaction ID" as "Copy the transaction".

The correct translation should be:
ტრანზაქციის ID და გამომავალი ინდექსის კოპირება
```

```
        <source>Copy after fee</source>
        <translation>დამატებითი საკომისიოს კოპირება</translation>
    
YES, The translation is problematic. The word "additional" (დამატებითი) in the translation is not present in the source text. The source text "Copy after fee" implies copying the amount that remains after deducting the fee.
Correct translation: საფასურის შემდეგ ასლის აღება
```

```
        <source>Are you sure you wish to close the wallet &lt;i&gt;%1&lt;/i&gt;?</source>
        <translation>დაიხუროს საფულე&lt;i&gt;%1&lt;/i&gt; ?</translation>
    
YES: The translation is grammatically incorrect and awkward. It should be phrased as a question asking if the user wants to close the wallet.
Correct translation: დაადასტურეთ, რომ გსურთ საფულის &lt;i&gt;%1&lt;/i&gt; დახურვა?
```

```
        <source>Encrypt Wallet</source>
        <translation>საფულის დაცვა [Encrypt Wallet]</translation>
    
YES, The translation is problematic because it does not accurately translate the source text. The Georgian phrase "საფულის დაცვა" translates to "Protect wallet", not "Encrypt Wallet". Additionally, the phrase "[Encrypt Wallet]" in brackets is redundant and not part of the original English source text.

The correct translation should be "საფულის დაშიფვრა".

NO
```

```
        <source>Create</source>
        <translation>ახალი</translation>
    
YES, The translation is inaccurate and doesn't capture the meaning of "Create" in the context of Bitcoin. "ახალი" means "new". A more appropriate translation for "Create" in this context would be "შექმნა".

YES, The translation is inaccurate and doesn't capture the meaning of "Create" in the context of Bitcoin. "ახალი" means "new". A more appropriate translation for "Create" in this context would be "შექმნა".
        <source>Create</source>
        <translation>შექმნა</translation>
```

```
        <source>The address associated with this address list entry. This can only be modified for sending addresses.</source>
        <translation>მისამართების სიის ამ ჩანაწერთან მისამართი ასოცირებული. მისი შეცვლა შეიძლება მხოლოდ გაგზავნის მისამართის შემთხვევაში.</translation>
    
YES, The Georgian translation incorrectly translates "This can only be modified for sending addresses." into "its modification is possible only in case of sending address". The correct translation should be "Its modification is possible only for sending addresses.".
The correct translation is: მისამართების სიის ამ ჩანაწერთან დაკავშირებული მისამართი. მისი შეცვლა შესაძლებელია მხოლოდ გაგზავნის მისამართებისთვის.
```

```
        <source>Path already exists, and is not a directory.</source>
        <translation>მისამართი უკვე არსებობს და არ წარმოადგენს კატალოგს.</translation>
    
YES, The word "address" is translated to "მისამართი" which means "address" in English. However, in the context of Bitcoin, "address" can also refer to a Bitcoin wallet address or a P2P network address. The word "directory" is translated to "კატალოგს" which means "catalog" in English, which is not appropriate in this context. A more suitable translation for "directory" in this context would be "საქაღალდე" or "დირექტორია".

The correct translation should be:
"მისამართი უკვე არსებობს და არ წარმოადგენს საქაღალდეს."
```

```
        <source>Error: Specified data directory "%1" cannot be created.</source>
        <translation>შეცდომა: მითითებულ მონაცემთა დირექტორია „%1“ არ არის შექმნილი.</translation>
    
YES: The translation uses "არ არის შექმნილი" (is not created) which is a negation of the creation action. The original English implies that the directory *cannot* be created. A more accurate translation would convey the inability to create.

Correct translation: შეცდომა: მითითებული მონაცემთა დირექტორია „%1“ არ იქმნება.
```

```
        <source>Use a custom data directory:</source>
        <translation>მითითებული კატალოგის გამოყენება:</translation>
    
YES, The translation is incorrect and misleading. The source text asks to use a custom data directory, while the translation states to use a specified catalog.

Correct translation: მორგებული მონაცემთა დირექტორიის გამოყენება:
```

```
        <source>%1 is shutting down…</source>
        <translation> დახურულია %1...</translation>
    
YES, The translation of "shutting down" is incorrect. The word "დახურულია" means "closed" or "has been closed", which implies a completed action. The English phrase "shutting down" implies an ongoing process. A more accurate translation would convey this ongoing nature.

The correct translation should be: "Closed %1..."
```

```
        <source>Progress increase per hour</source>
        <translation>პროგრესი გაუმჯობესდება ერთ საათში</translation>
    
YES, The translation is problematic because it implies that progress will improve within an hour, whereas the original text states that progress *increases per hour*. The translation uses "გაუმჯობესდება" (will improve) instead of something like "იზრდება" (increases).

The correct translation should be: "პროგრესი იზრდება ერთ საათში"
```

```
        <source>Reset Options</source>
        <translation>დაბრუნების ოპციები</translation>
    
YES, The translation is incorrect and should be "გადატვირთვის პარამეტრები" or "საკონტროლო პარამეტრების გადატვირთვა". The word "დაბრუნების" means "return" or "coming back", while "Reset Options" means to revert settings to their default values.
<source>Reset Options</source>
<translation>გადატვირთვის პარამეტრები</translation>
```

```
        <source>Choose the default subdivision unit to show in the interface and when sending coins.</source>
        <translation>აირჩიეთ გასაგზავნი თანხის ნაგულისხმევი ერთეული.</translation>
    
YES - The translation is inaccurate. It translates "subdivision unit" as "unit of the amount to be sent". The correct translation should refer to the unit of Bitcoin, such as satoshi or BTC.

Correct translation: აირჩიეთ ნაგულისხმევი ქვედანაყოფი, რომელიც ნაჩვენები იქნება ინტერფეისში და მონეტების გაგზავნისას.
```

```
        <source>This change would require a client restart.</source>
        <translation>ამ ცვლილებების ძალაში შესასვლელად საჭიროა კლიენტის დახურვა და ხელახალი გაშვება.</translation>
    
YES. The provided translation uses a literal translation of "change" which means "changes" in Georgian. However, in the context of Bitcoin, "change" refers to the concept of returning unspent transaction outputs, not general modifications. The Georgian word for this concept is "ცვლილება" (tsvlileba) or "ნასყიდი" (naskidi). The current translation implies that the changes themselves require a restart, rather than the implementation of the change.

A more accurate translation would be: "ამ ცვლილების დასამუშავებლად საჭიროა კლიენტის გადატვირთვა." (Am tsvlilobis dasamuSaveblad saWiroa klientis gadatvirTva.) This translates to "To process this change, a client restart is required."
```

```
        <source>Total of transactions that have yet to be confirmed, and do not yet count toward the spendable balance</source>
        <translation>დასადასტურებელი ტრანსაქციების საერთო რაოდენობა, რომლებიც ჯერ არ არის ასახული ბალანსში</translation>
    
UNK_LANG
```

```
        <source>Mined balance that has not yet matured</source>
        <translation>მოპოვებული თანხა, რომელიც ჯერ არ არის მზადყოფნაში</translation>
    
YES. The translation is problematic because "მზადყოფნაში" (mzadopnashi) which means "readiness" or "preparedness" is not the correct term to describe the maturity of a mined Bitcoin balance. Bitcoin transactions take time to mature (confirmations).

The correct translation should convey the idea of not being confirmed or not being ready for spending yet.

Correct translation: მოპოვებული ბალანსი, რომელიც ჯერ არ არის დამტკიცებული. (Mopovebuli balansi, romelic jer aris damtkicebuli.) - "Mined balance that is not yet confirmed."
```

```
        <source>Could not sign any more inputs.</source>
        <translation>მეტი შენატანის ხელმოწერა ვერ მოხერხდა.</translation>
    
YES, the translation is problematic. The word "შენატანის" (shenatanis) means "deposit" or "contribution", which is not the correct translation for "inputs" in the context of Bitcoin transactions. The correct translation should refer to the inputs of a transaction.

NO
```

```
        <source>Transaction broadcast successfully! Transaction ID: %1</source>
        <translation>ტრანზაქციის მონაცემების გაგზავნა წარმატებით დასრულდა! ტრანზაქციის ID: %1</translation>
    
YES. The translation is grammatically incorrect and awkward in Georgian. The word "მონაცემების" (data) is unnecessary and makes the sentence sound unnatural.

A more natural and accurate translation would be:

"ტრანზაქცია წარმატებით გავრცელდა! ტრანზაქციის ID: %1"
```

```
        <source>Transaction broadcast failed: %1</source>
        <translation>ტრანზაქციის მონაცემების გაგზავნა ვერ მოხერხდა: %1</translation>
    
YES, The translation is problematic. While the translation conveys the general meaning of the source text, the word "მონაცემების" (data) is unnecessary and makes the translation sound unnatural in the context of Bitcoin transactions. The core issue is a slight over-translation and lack of idiomatic phrasing.

Correct translation: ტრანზაქციის გაგზავნა ვერ მოხერხდა: %1
```

```
        <source>Transaction is missing some information about inputs.</source>
        <translation>ტრანზაქციას აკლია გარკვეული ინფორმაცია შენატანის შესახებ.</translation>
    
YES, the translation is problematic because it incorrectly translates "inputs" to "შენატანის" (shenatanis) which means "contribution" or "donation" in Georgian. In the context of Bitcoin transactions, "inputs" refers to the source of funds being spent, not contributions.

The correct translation should be:
<translation>ტრანზაქციას აკლია გარკვეული ინფორმაცია შემოტანის შესახებ.</translation>
```

```
        <source>Cannot start bitcoin: click-to-pay handler</source>
        <translation>ვერ გაიშვა bitcoin: click-to-pay</translation>
    
YES - The translation is missing "handler". The correct translation is "ვერ გაიშვა bitcoin: click-to-pay handler".
```

```
        <source>'bitcoin://' is not a valid URI. Use 'bitcoin:' instead.</source>
        <translation>„bitcoin://“ არ არის სწორი URI. ამის ნაცვლად გამოიყენეთ „bitcoin:“.</translation>
    
YES. The translation incorrectly translates "URI" to "URI" without providing a Georgian equivalent or transliteration, which is an uncommon practice for technical terms. The correct translation should use a Georgian equivalent or transliteration for "URI".

Correct translation: „bitcoin://“ არ არის სწორი ზოგადი მისამართის აღმნიშვნელი (URI). ამის ნაცვლად გამოიყენეთ „bitcoin:“ .
```

```
        <source>Peer</source>
        <extracomment>Title of Peers Table column which contains a unique number used to identify a connection.</extracomment>
        <translation>თანაბარი</translation>
    
YES - The translation "თანაბარი" means "equal" or "even" in Georgian, which is not the correct translation for "Peer" in the context of Bitcoin connections. The correct translation for "Peer" in this context would be "თანამოსაუბრე" or "კოლეგა".
Correct translation: თანამოსაუბრე
```

```
        <source>N/A</source>
        <translation>მიუწვდ.</translation>
    
YES, The translation is problematic because it is an incomplete abbreviation of the English word "Not Available" and does not accurately convey the meaning in Georgian. The correct translation for "N/A" in this context would be "არ არის ხელმისაწვდომი".
მიუწვდ.
```

```
        <source>Last Block</source>
        <translation>ბოლო "ბლოკი"</translation>
    
YES, The translation is problematic because it includes unnecessary quotation marks around the word "ბლოკი".

The correct translation is:
<translation>ბოლო ბლოკი</translation>
```

```
        <source>Open</source>
        <translation>შექმნა</translation>
    
YES, The Georgian word "შექმნა" means "create" and is not a good translation for "Open" in the context of Bitcoin. In Bitcoin, "open" usually refers to opening a wallet or a transaction, for which a more appropriate translation would be "გახსნა".

The correct translation is:
<translation>გახსნა</translation>
```

```
        <source>Use this form to request payments. All fields are &lt;b&gt;optional&lt;/b&gt;.</source>
        <translation>გამოიყენეთ ეს ფორმა გადახდის მოთხოვნისათვის. ყველა ველი &lt;b&gt;არააუცილებელია&lt;/b&gt;.</translation>
    
UNK_LANG
```

```
        <source>An optional amount to request. Leave this empty or zero to not request a specific amount.</source>
        <translation>მოთხოვნის მოცულობა. არააუცილებელია. ჩაწერეთ 0 ან დატოვეთ ცარიელი, თუ არ მოითხოვება კონკრეტული მოცულობა.</translation>
    
YES - The translation is problematic because it uses the word "მოცულობა" which means "volume" or "capacity" in Georgian, not "amount" or "sum" as intended in the context of a Bitcoin transaction. The correct word for "amount" in this context would be "თანხა". Additionally, the sentence structure and word choice are a bit awkward.

Correct translation: მოთხოვნის თანხა. არასავალდებულოა. დატოვეთ ცარიელი ან ჩაწერეთ 0, თუ არ ითხოვთ კონკრეტულ თანხას.
```

```
        <source>Show the selected request (does the same as double clicking an entry)</source>
        <translation>არჩეული მოთხოვნის ჩვენება (იგივეა, რაც ჩანაწერზე ორჯერ ჩხვლეტა)</translation>
    
YES: The Georgian word "ჩხვლეტა" (chkhleta) translates to "prick" or "stab", which is inappropriate for the context of clicking on an entry. A more suitable translation would be "დაწკაპება" (datskapéba), meaning "click".

Here's the corrected translation:
<translation>არჩეული მოთხოვნის ჩვენება (იგივეა, რაც ჩანაწერზე ორჯერ დაწკაპება)</translation>
```

```
        <source>Copy label</source>
        <translation>კოპირება ჭდე</translation>
    
YES, The translation is problematic. The Georgian word "ჭდე" is not a correct translation for "label" in this context. The correct translation for "label" in the context of Bitcoin or general user interfaces would be "ეტიკეტი" or "სახელწოდება".

Correct translation: დააკოპირეთ ეტიკეტი
```

```
        <source>Verify</source>
        <translation>შემოწმება </translation>
    
YES, The Georgian translation is problematic because of the trailing whitespace, which is not present in the source text.
Correct translation: შემოწმება
```

```
        <source>Request payment to %1</source>
        <translation>%1-ის გადაზდის მოთხოვნა</translation>
    
YES, The translation is problematic because it does not correctly convey the meaning of the source text. The source text "Request payment to %1" implies that the user is requesting someone to send payment to a specific address or person represented by %1. The provided translation "%1-ის გადაზდის მოთხოვნა" translates to "Request for payment to %1", which is grammatically incorrect and awkward in Georgian. A more accurate and natural translation would be "გადახდის მოთხოვნა %1-ისთვის".
Additionally, the original translation uses "გადაზდის" which is a misspelling of "გადახდის" (payment).

Correct translation: გადახდის მოთხოვნა %1-ისთვის
```

```
        <source>After Fee:</source>
        <translation>დამატებითი საკომისიო:</translation>
    
YES, The translation is problematic because it does not accurately convey the meaning of "After Fee". In the context of Bitcoin, "After Fee" refers to the amount remaining after a transaction fee has been deducted, not an additional fee.

The correct translation should be:

<translation>გადასახადის შემდეგ:</translation>
```

```
        <source>If this is activated, but the change address is empty or invalid, change will be sent to a newly generated address.</source>
        <translation>ამის გააქტიურებისას თუ ხურდის მისამართი ცარიელია ან არასწორია, ხურდა გაიგზავნება ახლად გენერირებულ მისამართებზე.</translation>
    
YES - The translation uses the plural "მისამართებზე" (addresses) when the source text uses the singular "address". The correct translation should be singular.
NO, the translation is unproblematic.
```

```
        <source>Custom change address</source>
        <translation>ხურდის მისამართი</translation>
    
YES, The translation uses the word "ხურდა" which translates to "small change" or "coins" and does not accurately convey the meaning of "custom change address" in the context of Bitcoin. The correct translation should refer to a user-defined address for receiving change.
The correct translation is: მორგებული ცვლილების მისამართი
```

```
        <source>Transaction Fee:</source>
        <translation>ტრანსაქციის საფასური - საკომისიო:</translation>
    
YES, The translation of "Transaction Fee:" to "ტრანსაქციის საფასური - საკომისიო:" is problematic because it includes redundant information. "საფასური" and "საკომისიო" both translate to "fee" or "commission." In the context of Bitcoin, "Transaction Fee" is typically translated as a single term.

Correct translation:
<translation>ტრანსაქციის საკომისიო:</translation>
```

```
        <source>Copy after fee</source>
        <translation>დამატებითი საკომისიოს კოპირება</translation>
    
YES, The translation is problematic. The word "additional" (დამატებითი) in the translation is not present in the source text. The source text "Copy after fee" implies copying the amount that remains after deducting the fee.
Correct translation: საფასურის შემდეგ ასლის აღება
```

```
        <source>%1 to %2</source>
        <translation>%1-დან %2-ში</translation>
    
YES, The translation is problematic because it uses the wrong case for the second word. The correct translation should be "%1-დან %2-მდე".
```

```
        <source>You can increase the fee later (signals Replace-By-Fee, BIP-125).</source>
        <translation>საკომისიო [fee] შეგიძლიათ შცვალოთ მოგვიანებით (სიგნალები Replace-By-Fee, BIP-125}.
 </translation>
    
YES - The "fee" specifier is not correctly transferred and a typo is present in the translation.
Correct translation: საკომისიო შეგიძლიათ ცვალოთ მოგვიანებით (სიგნალები Replace-By-Fee, BIP-125).
```

```
        <source>The total exceeds your balance when the %1 transaction fee is included.</source>
        <translation>საკომისიო %1-ის დამატების შემდეგ თანხა აჭარბებს თქვენს ბალანსს</translation>
    
YES: The translation does not accurately reflect the source text. It states "the amount exceeds your balance after adding the commission of %1", which is a different meaning than "The total exceeds your balance when the %1 transaction fee is included." The original English implies that the total amount *including* the fee is the problem, not that the fee itself is being added to an already exceeding amount.

Correct translation:
<translation>ჯამური თანხა, %1 ტრანზაქციის საკომისიოს ჩათვლით, აღემატება თქვენს ბალანსს</translation>
```

```
        <source>Warning: Invalid Bitcoin address</source>
        <translation>ყურადღება: არასწორია Bitcoin-მისამართი</translation>
    
YES, The word "address" is not translated into Georgian correctly. The correct Georgian word for "address" in this context is "მისამართი".
Warning: Invalid Bitcoin address
ყურადღება: არასწორი Bitcoin მისამართი
```

```
        <source>Warning: Unknown change address</source>
        <translation>ყურადღება: უცნობია ხურდის მისამართი</translation>
    
YES: The translation uses "ხურდის მისამართი" which means "coin's address" or "change's address" which is not the standard Bitcoin terminology for a change address. The correct translation for a change address in Bitcoin context is "მისამართი ცვლილებისთვის".
ყურადღება: უცნობია მისამართი ცვლილებისთვის
```

```
        <source>A message that was attached to the bitcoin: URI which will be stored with the transaction for your reference. Note: This message will not be sent over the Bitcoin network.</source>
        <translation>მესიჯი, რომელიც თან ერთვის მონეტებს:  URI, რომელიც შეინახება ტრანსაქციასთან ერთად თქვენთვის. შენიშვნა: მესიჯი არ გაყვება გადახდას ბითქოინის ქსელში.</translation>
    
YES: The translation inaccurately translates "bitcoin: URI" as "monetebs: URI". The correct translation should be "ბიტკოინი: URI".

NO: მესიჯი, რომელიც თან ერთვის ბიტკოინი: URI, რომელიც შეინახება ტრანსაქციასთან ერთად თქვენთვის. შენიშვნა: მესიჯი არ გაყვება გადახდას ბითქოინის ქსელში.
```

```
        <source>press q to shutdown</source>
        <translation>დახურვა 'q'</translation>
    
YES, The translation is inaccurate. The word 'shutdown' is translated to 'close' but it should be translated to 'shutdown'.
The correct translation is: დახურვა q
```

```
        <source>Inputs</source>
        <translation>ხარჯები</translation>
    
YES, The translation is problematic. The Georgian word "ხარჯები" (khardjebi) translates to "expenses" or "expenditures" in English, which is not an accurate translation for "Inputs" in the context of Bitcoin transactions. In Bitcoin, "inputs" refer to the source of the funds being spent. A more appropriate translation would be "შემავალი" (shemavali) or "შესატანი" (shesatani).

The correct translation is:
<translation>შემავალი</translation>
```

```
        <source>Confirming (%1 of %2 recommended confirmations)</source>
        <translation>დადასტურებულია (%1,  რეკომენდებულია %2)</translation>
    
YES - The translation is inaccurate and doesn't convey the intended meaning. It seems to have misinterpreted "of" and omitted the concept of "recommendations" in the correct context.

Correct translation: დადასტურება (%1-დან %2 რეკომენდებული დადასტურებიდან)
```

```
        <source>Confirmed (%1 confirmations)</source>
        <translation>დადასტურებულია (%1დასტური)</translation>
    
YES, The translation has an issue with spacing. The format specifier "%1" should be followed by a space.
Correct translation: დადასტურებულია (%1 დასტური)
```

```
        <source>Immature (%1 confirmations, will be available after %2)</source>
        <translation>არ არის მომწიფებული (%1 დასტური, საჭიროა სულ %2)</translation>
    
YES, The translation incorrectly uses the word "available" instead of "confirmations" in the Georgian translation.
The correct translation should be: "არ არის მომწიფებული (%1 დასტური, ხელმისაწვდომი იქნება %2-ის შემდეგ)".
```

```
        <source>(n/a)</source>
        <translation>(მიუწვდ.)</translation>
    
YES, The provided translation is problematic. The source text "(n/a)" likely means "not applicable" or "not available". The Georgian translation "(მიუწვდ.)" is an abbreviation for "მიუწვდომელი" which means "inaccessible" or "unavailable". While similar, it's not a direct or accurate translation of "(n/a)" in the context of technical or financial information where "n/a" is commonly used to indicate that a particular piece of data is not provided or does not apply.

A more appropriate translation for "(n/a)" in this context would be "(ვ.ტ.)" which is an abbreviation for "ვერ გავაკეთე" meaning "not done" or "not available", or simply using a common transliteration like "(ენ/ე)" which directly represents "n/a". Given the context is Bitcoin, which is technical, a more standard representation would be better.

Correct translation: (ვ.ტ.)
```

```
        <source>Last month</source>
        <translation>ბოლო თვის</translation>
    
YES, The translation for "Last month" is "ბოლო თვის". This is incorrect. "Last month" translates to "გასულ თვეში" in Georgian. The provided translation "ბოლო თვის" means "of the last month" and implies possession or a part of something, which is not the intended meaning.

Correct translation: გასულ თვეში
```

```
        <source>Copy label</source>
        <translation>კოპირება ჭდე</translation>
    
YES, The translation is problematic. The Georgian word "ჭდე" is not a correct translation for "label" in this context. The correct translation for "label" in the context of Bitcoin or general user interfaces would be "ეტიკეტი" or "სახელწოდება".

Correct translation: დააკოპირეთ ეტიკეტი
```

```
        <source>Copy transaction ID</source>
        <translation>ტრანზაქციის დაკოპირება ID</translation>
    
YES - The Georgian translation is not accurate. The verb "დაკოპირება" (dakorpeba) means "to copy" and should be in imperative form, "დააკოპირეთ" (dakorpiet). Also, the word order is slightly off. The correct translation should be "დააკოპირეთ ტრანზაქციის ID" (dakorpiet tranzakciis ID), which means "Copy the transaction ID".
The correct translation is: <translation>დააკოპირეთ ტრანზაქციის ID</translation>
```

```
        <source>Copy full transaction details</source>
        <translation>სრული ტრანზაქციის კოპირება დეტალები</translation>
    
YES. The Georgian translation contains an awkward phrasing and misplaces the word "details". The direct translation of "Copy full transaction details" should be more natural and grammatically correct in Georgian.

"სრული ტრანზაქციის დეტალების კოპირება"
```

```
        <source>Increase transaction fee</source>
        <translation>ტრანზაქციის გაზრდა საფასური</translation>
    
YES, The Georgian translation is grammatically incorrect and sounds unnatural. The word order is wrong.
Correct translation: ტრანზაქციის საფასურის გაზრდა
```

```
        <source>There was an error trying to save the transaction history to %1.</source>
        <translation>შეცდომა %1-ში ტრანსაქციების შენახვის მცდელობისას.</translation>
    
YES, The translation is problematic because it misinterprets "save the transaction history to %1" as "in %1", which is not accurate. The correct translation should reflect the action of saving the history *to* a location or entity represented by %1.

Correct translation: შეცდომა მოხდა ტრანზაქციების ისტორიის %1-ზე შენახვის მცდელობისას.
```

```
        <source>Error creating %s</source>
        <translation>შეცდომა%s-ის შექმნისას</translation>
    
YES, The translation is problematic because of an incorrect word order and missing space. The correct translation should be "შეცდომა %s-ის შექმნისას".
```

```
        <source>Error opening block database</source>
        <translation>ბლოკთა ბაზის შექმნა ვერ მოხერხდა</translation>
    
YES, The translation is inaccurate. The source text means "Error opening block database", but the translation means "Failed to create block database". The correct translation should be "ბლოკთა ბაზის გახსნა ვერ მოხერხდა".
```

```
        <source>Incorrect or no genesis block found. Wrong datadir for network?</source>
        <translation>საწყისი ბლოკი არ არსებობს ან არასწორია. ქსელის მონაცემთა კატალოგი datadir ხომ არის არასწორი?</translation>
    
YES - The translation is problematic because it adds an unnecessary question mark at the end, which is not present in the source text. Additionally, the phrasing "ქსელის მონაცემთა კატალოგი datadir ხომ არის არასწორი?" is a bit awkward and could be more direct.

Correct translation: საწყისი ბლოკი არ არსებობს ან არასწორია. ქსელის მონაცემთა კატალოგი datadir ხომ არ არის არასწორი?
```

```
        <source>Transaction amount too small</source>
        <translation>ტრანსაქციების რაოდენობა ძალიან ცოტაა</translation>
    
YES, the translation is inaccurate and does not convey the intended meaning. The source text "Transaction amount too small" refers to the value of a Bitcoin transaction, while the translation "ტრანსაქციების რაოდენობა ძალიან ცოტაა" means "The number of transactions is too small."

The correct translation should refer to the *amount* of the transaction, not the *number* of transactions.

Correct translation:
<translation>ტრანზაქციის თანხა ძალიან მცირეა</translation>
```
</details>
