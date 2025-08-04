# Translations Review by LLM (✨ experimental)

The review quality depends on the LLM and the language. Currently, a fast LLM without rate limits is used. If you are interested in better quality for a specific language, please file an issue to ask for it to be re-run with a stronger model.



<details><summary>te</summary>

[If the result is of low quality, please file an issue to find a better LLM for this language.](../../issues/new?title=%5Bte%5D%20low%20quality)


```
        <source>Enter address or label to search</source>
        <translation>చిరునామా లేదా ఏదైనా పేరును వెతకండి</translation>
    
YES: The Telugu translation is inaccurate. The word "label" is translated as "any name" which is not the intended meaning. In the context of Bitcoin, "label" refers to a user-defined identifier for an address.

Correct translation: చిరునామా లేదా లేబుల్‌ను వెతకండి
```

```
        <source>Copy Label</source>
        <translation>కాపీ  ఉల్లాకు</translation>
    
YES, The translation is incorrect. The word "ఉల్లాకు" (ullaku) is not the correct Telugu word for "label". The correct word for "label" in this context would be "లేబుల్" (label) or "పేరు" (peru).

NO
```

```
        <source>There was an error trying to save the address list to %1. Please try again.</source>
        <extracomment>An error message. %1 is a stand-in argument for the name of the file we attempted to save to.</extracomment>
        <translation>చిరునామా పట్టికను %1 లోనికి ప్రోదుపరుచుటలో లోపము. మరుల ప్రయత్నించి చుడండి.</translation>
    
YES, The translation uses an inappropriate word for "save" which is "ప్రొదుపరుచుట" (prodhuparuchuṭa). The correct word for "save" in this context would be "సేవ్ చేయుట" (sēv cēyuṭa) or "భద్రపరచుట" (bhadraparachūṭa).
The translation also uses a slightly awkward phrasing for "Please try again", which is "మరుల ప్రయత్నించి చుడండి" (marula prayatnin̄ci cuḍaṇḍi). A more natural phrasing would be "దయచేసి మళ్ళీ ప్రయత్నించండి" (dayacēsi maḷḷī prayatnin̄caṇḍi).

Here is the corrected translation:
<translation>చిరునామా జాబితాను %1 కు సేవ్ చేయడంలో లోపం జరిగింది. దయచేసి మళ్ళీ ప్రయత్నించండి.</translation>
```

```
        <source>Label</source>
        <translation>ఉల్లాకు</translation>
    
YES, The Telugu word "ఉల్లాకు" (ullaku) is not a standard or recognized word. It seems like a nonsensical or misspelled word. The correct translation for "Label" in the context of Bitcoin or general use is "లేబుల్" (label) or "పేరు" (peru - meaning name/tag).

NO
```

```
        <source>(no label)</source>
        <translation>( ఉల్లాకు లేదు )</translation>
    
YES, The Telugu translation is grammatically incorrect and does not convey the intended meaning. The word "ఉల్లాకు" is not a standard Telugu word and seems to be a misspelling or an invented word. The intended meaning of "(no label)" in the context of Bitcoin transactions would typically refer to a transaction that hasn't been assigned a user-defined label or description. A more appropriate translation would be "(లేబుల్ లేదు)" which means "(no label)".

(లేబుల్ లేదు)
```

```
        <source>Are you sure you wish to encrypt your wallet?</source>
        <translation>మీరు ఖచ్చితంగా మీ జోలెని సంకేతపరచాలని కోరుకుంటున్నారా?</translation>
    
YES - The translation uses the word "జోలెని" which means "bag" or "pouch", instead of "wallet". The correct translation for "wallet" in this context is "వాలెట్".

మీరు ఖచ్చితంగా మీ వాలెట్‌ను సంకేతపరచాలని కోరుకుంటున్నారా?
```

```
        <source>Wallet encrypted</source>
        <translation>జోలె సంకేతపరబడింది</translation>
    
YES, The Telugu translation is incorrect. "Wallet encrypted" translates to "వాలెట్ గుప్తీకరించబడింది" in Telugu. The provided translation "జోలె సంకేతపరబడింది" means "The basket is encrypted".

Correct translation: వాలెట్ గుప్తీకరించబడింది
```

```
        <source>Your wallet is now encrypted. </source>
        <translation>cheraveyu chirunama</translation>
    
YES, The translation is inaccurate and does not convey the meaning of the source text. The source text is "Your wallet is now encrypted." and the translation "cheraveyu chirunama" is nonsensical in Telugu.

Correct translation: మీ వాలెట్ ఇప్పుడు ఎన్‌క్రిప్ట్ చేయబడింది.
```

```
        <source>Wallet encryption failed</source>
        <translation>జోలె సంకేతపరచడం విఫలమయ్యింది</translation>
    
YES, The translation is not accurate. The word "జోలె" means "cradle" which is not related to "wallet". The correct translation for "wallet" in Telugu is "పర్సు".
The correct translation is: పర్సు గుప్తీకరణ విఫలమైంది
```

```
        <source>Wallet encryption failed due to an internal error. Your wallet was not encrypted.</source>
        <translation>lopali tappidam valla mee yokka wallet encryption samapthamu avaledu</translation>
    
YES - The translation uses an incorrect word for "wallet" ("lopali tappidam" which means "inside lost") and the word for "failed" ("samapthamu avaledu" which means "did not succeed"). The correct translation for "wallet encryption failed" is "Wallet encryption విఫలమైంది".

NO
```

```
        <source>Banned Until</source>
        <translation>వరకు నిషేధించబడింది</translation>
    
UNK_LANG
```

```
        <source>Settings file %1 might be corrupt or invalid.</source>
        <translation>సెట్టింగ్‌ల ఫైల్ 1 %1 పాడై ఉండవచ్చు లేదా చెల్లదు</translation>
    
YES, The translation is problematic because the format specifier '%1' has been placed after the word "ఫైల్" instead of before it. This also results in a grammatical error in the Telugu sentence.

Correct translation: సెట్టింగ్‌ల ఫైల్ %1 పాడై ఉండవచ్చు లేదా చెల్లదు.
```

```
        <source>Full Relay</source>
        <extracomment>Peer connection type that relays all network information.</extracomment>
        <translation>పూర్తిగా  ఏర్పరచుట</translation>
    
YES, The translation for "Full Relay" is not accurate in the context of Bitcoin. The Telugu phrase "పూర్తిగా ఏర్పరచుట" means "fully forming" or "fully establishing," which does not convey the meaning of relaying network information. The correct translation should reflect the act of relaying or forwarding all network information.

Correct translation: నెట్‌వర్క్ సమాచారాన్ని పూర్తిగా ఫార్వార్డ్ చేయుట
```

```
        <source>Block Relay</source>
        <extracomment>Peer connection type that relays network information about blocks and not transactions or addresses.</extracomment>
        <translation>ఏర్పాటు చేయుటను నిరోధించండి</translation>
    
YES, the translation is incorrect and does not convey the meaning of the source text. The source text "Block Relay" refers to a method of relaying information about blocks on the Bitcoin network. The provided translation "ఏర్పాటు చేయుటను నిరోధించండి" translates to "Prevent establishing," which is completely unrelated to the context.

NO
```

```
        <source>Feeler</source>
        <extracomment>Short-lived peer connection type that tests the aliveness of known addresses.</extracomment>
        <translation>అనుభూతి</translation>
    
YES. The translation of "Feeler" as "అనుభూతి" (Anubhūti) is inaccurate in the context of Bitcoin networking. "Anubhūti" means "feeling" or "experience" in Telugu, which is not relevant here. The extarcomment clarifies that "Feeler" is a type of peer connection that tests aliveness. A more accurate translation would reflect this testing or probing nature.

Correct translation: **పరీక్షించేది** (Parīkṣin̄cēdi) - This translates to "tester" or "one that tests," which fits the context of a connection type that tests the aliveness of known addresses.
```

```
        <source>About Qt</source>
        <translation>గురించి  Qt</translation>
    
YES
The Telugu word "గురించి" (gurinchi) means "about". However, there is an extra space between "గురించి" and "Qt".

Correct translation: గురించి Qt
```

```
        <source>Create a new wallet</source>
        <translation>&lt;div&gt;&lt;/div&gt;</translation>
    
YES. The translation is completely missing the meaning of the source text and contains extraneous HTML tags.
Correct translation: కొత్త వాలెట్ ను సృష్టించండి
```

```
        <source>Wallet:</source>
        <translation>ధనమును తీసుకొనిపోవు సంచి</translation>
    
YES, The translation is inaccurate and does not convey the intended meaning in the context of Bitcoin. The Telugu translation provided means "money taking bag" which is not the correct term for a Bitcoin wallet.

Correct translation: వాలెట్
```

```
        <source>Backup wallet to another location</source>
        <translation>మరొక ప్రదేశానికి జోలెను బ్యాకప్ చెయండి</translation>
    
YES, The translation is problematic because "address" is translated as "జోలె" (jole), which means "cradle" or "hammock" in Telugu, instead of a Bitcoin wallet address.

The correct translation should be:
<translation>మరొక ప్రదేశానికి వాలెట్‌ను బ్యాకప్ చేయండి</translation>
```

```
        <source>Backup Wallet…</source>
        <translation>బ్యాకప్ వాలెట్...</translation>
    
UNK_LANG
```

```
        <source>Request payments (generates QR codes and bitcoin: URIs)</source>
        <translation>చెల్లింపులను అభ్యర్థించండి (QR కోడ్‌లు మరియు బిట్‌కాయిన్‌లను ఉత్పత్తి చేస్తుంది: URIలు)</translation>
    
YES, The translation has an error. The phrase "bitcoin: URIs" is translated as "బిట్‌కాయిన్‌లను ఉత్పత్తి చేస్తుంది: URIలు" which means "produces bitcoins: URIs". The word "produces" should be "generates" as in the source text. Also, the source text says "generates QR codes and bitcoin: URIs" but the translation says "produces bitcoins: URIs".

NO
```

```
        <source>Information</source>
        <translation>వర్తమానము</translation>
    
YES
The translation of "Information" to "వర్తమానము" (Vartamānamu) is incorrect in this context. "వర్తమానము" means "present" or "current" and does not convey the meaning of "information." In the context of Bitcoin, the appropriate Telugu word for "Information" would be "సమాచారం" (Samācāraṁ).

Correct translation: సమాచారం
```

```
        <source>Sending addresses</source>
        <translation>చిరునామా పంపుతోంది</translation>
    
YES, the translation is problematic because it is grammatically incorrect and does not accurately convey the meaning of the source text. The source text "Sending addresses" refers to multiple addresses from which Bitcoin is being sent, while the translation "చిరునామా పంపుతోంది" translates to "sending address" (singular) and implies the act of sending an address rather than the addresses from which funds are being sent.

The correct translation should be "పంపే చిరునామాలు" which means "sending addresses".

NO
```

```
        <source>Open a bitcoin: URI</source>
        <translation>బిట్‌కాయిన్‌ను తెరవండి: URI</translation>
    
YES, The translation is problematic because it misinterprets the English phrase "Open a bitcoin: URI". It translates "bitcoin" as a verb ("open bitcoin") instead of a noun referring to the cryptocurrency.

The correct translation should be:
<translation>ఒక బిట్‌కాయిన్: URIని తెరవండి</translation>
```

```
        <source>Restore a wallet from a backup file</source>
        <extracomment>Status tip for Restore Wallet menu item</extracomment>
        <translation>బ్యాకప్ ఫైల్ నుండి వాలెట్‌ను పునరుద్ధరించండి</translation>
    
UNK_LANG
```

```
        <source>(un)select all</source>
        <translation>ఎంచుకున్నవన్నీ తొలగించు</translation>
    
YES, The translation is problematic as it only translates "unselect all" and misses the "select all" part. The translation also uses "తొలగించు" which means "delete" instead of "unselect".
(un)select all: అన్నీ ఎంచుకోండి / ఎంచుకున్నవన్నీ తీసివేయండి
```

```
        <source>(no label)</source>
        <translation>( ఉల్లాకు లేదు )</translation>
    
YES, The Telugu translation is grammatically incorrect and does not convey the intended meaning. The word "ఉల్లాకు" is not a standard Telugu word and seems to be a misspelling or an invented word. The intended meaning of "(no label)" in the context of Bitcoin transactions would typically refer to a transaction that hasn't been assigned a user-defined label or description. A more appropriate translation would be "(లేబుల్ లేదు)" which means "(no label)".

(లేబుల్ లేదు)
```

```
        <source>change from %1 (%2)</source>
        <translation>నుండి మార్చండి %1 (%2)</translation>
    
YES, The Telugu translation is incorrect and does not convey the intended meaning of the English source text. The phrase "నుండి మార్చండి" literally translates to "change from" but in this context, it's likely referring to "change received" or "change amount".

Correct translation: %1 (%2) నుండి వచ్చిన మార్పు
```

```
        <source>Directory already exists. Add %1 if you intend to create a new directory here.</source>
        <translation>డైరెక్టరీ ఇప్పటికే ఉంది. %1 మీరు ఇక్కడ కొత్త డైరెక్టరీని సృష్టించాలనుకుంటే జోడించండి.</translation>
    
YES - The translation is grammatically awkward and the word order is incorrect. The '%1' format specifier should be placed before the text it modifies.

Correct Translation: డైరెక్టరీ ఇప్పటికే ఉంది. మీరు ఇక్కడ కొత్త డైరెక్టరీని సృష్టించాలనుకుంటే %1 జోడించండి.
```

```
        <source>Prune block storage to</source>
        <translation>స్టోరేజ్‌ను కత్తిరించు  బ్లాక్ చేయండి</translation>
    
YES. The translation is grammatically incorrect and the word order is unnatural for Telugu. The intended meaning is likely "Prune block storage".

NO. The translation is grammatically incorrect and the word order is unnatural for Telugu. The intended meaning is likely "Prune block storage".
The correct translation should be: "బ్లాక్ స్టోరేజ్‌ను తగ్గించండి" (block storage-nu tagginchandi) or "బ్లాక్ స్టోరేజ్‌ను కత్తిరించండి" (block storage-nu kattirinchandi). The provided translation "స్టోరేజ్‌ను కత్తిరించు బ్లాక్ చేయండి" (storage-nu kattirinchu block cheyandi) translates to "Prune storage, block it" which is not the intended meaning.
```

```
        <source>Could not read setting "%1", %2.</source>
        <translation>సెట్టింగ్ "%1", %2 చదవడం సాధ్యపడలేదు, .</translation>
    
YES, The translation is problematic because it adds an extra comma at the end. The correct translation should be: సెట్టింగ్ "%1", %2 చదవడం సాధ్యపడలేదు.
```

```
        <source>Wallet:</source>
        <translation>ధనమును తీసుకొనిపోవు సంచి</translation>
    
YES, The translation is inaccurate and does not convey the intended meaning in the context of Bitcoin. The Telugu translation provided means "money taking bag" which is not the correct term for a Bitcoin wallet.

Correct translation: వాలెట్
```

```
        <source>Label</source>
        <translation>ఉల్లాకు</translation>
    
YES, The Telugu word "ఉల్లాకు" (ullaku) is not a standard or recognized word. It seems like a nonsensical or misspelled word. The correct translation for "Label" in the context of Bitcoin or general use is "లేబుల్" (label) or "పేరు" (peru - meaning name/tag).

NO
```

```
        <source>(no label)</source>
        <translation>( ఉల్లాకు లేదు )</translation>
    
YES, The Telugu translation is grammatically incorrect and does not convey the intended meaning. The word "ఉల్లాకు" is not a standard Telugu word and seems to be a misspelling or an invented word. The intended meaning of "(no label)" in the context of Bitcoin transactions would typically refer to a transaction that hasn't been assigned a user-defined label or description. A more appropriate translation would be "(లేబుల్ లేదు)" which means "(no label)".

(లేబుల్ లేదు)
```

```
        <source>(no label)</source>
        <translation>( ఉల్లాకు లేదు )</translation>
    
YES, The Telugu translation is grammatically incorrect and does not convey the intended meaning. The word "ఉల్లాకు" is not a standard Telugu word and seems to be a misspelling or an invented word. The intended meaning of "(no label)" in the context of Bitcoin transactions would typically refer to a transaction that hasn't been assigned a user-defined label or description. A more appropriate translation would be "(లేబుల్ లేదు)" which means "(no label)".

(లేబుల్ లేదు)
```

```
        <source>Label</source>
        <translation>ఉల్లాకు</translation>
    
YES, The Telugu word "ఉల్లాకు" (ullaku) is not a standard or recognized word. It seems like a nonsensical or misspelled word. The correct translation for "Label" in the context of Bitcoin or general use is "లేబుల్" (label) or "పేరు" (peru - meaning name/tag).

NO
```

```
        <source>(no label)</source>
        <translation>( ఉల్లాకు లేదు )</translation>
    
YES, The Telugu translation is grammatically incorrect and does not convey the intended meaning. The word "ఉల్లాకు" is not a standard Telugu word and seems to be a misspelling or an invented word. The intended meaning of "(no label)" in the context of Bitcoin transactions would typically refer to a transaction that hasn't been assigned a user-defined label or description. A more appropriate translation would be "(లేబుల్ లేదు)" which means "(no label)".

(లేబుల్ లేదు)
```

```
        <source>Label</source>
        <translation>ఉల్లాకు</translation>
    
YES, The Telugu word "ఉల్లాకు" (ullaku) is not a standard or recognized word. It seems like a nonsensical or misspelled word. The correct translation for "Label" in the context of Bitcoin or general use is "లేబుల్" (label) or "పేరు" (peru - meaning name/tag).

NO
```

```
        <source>Create a new wallet</source>
        <translation>&lt;div&gt;&lt;/div&gt;</translation>
    
YES. The translation is completely missing the meaning of the source text and contains extraneous HTML tags.
Correct translation: కొత్త వాలెట్ ను సృష్టించండి
```

```
        <source>Backup Wallet</source>
        <translation>బ్యాకప్ వాలెట్</translation>
    
UNK_LANG
```

```
        <source>Verifying blocks…</source>
        <translation>బ్లాక్‌లను ధృవీకరిపబచున్నవి…</translation>
    
YES, The translation is not accurate. The word "ధృవీకరిపబచున్నవి" is not a standard Telugu word for "verifying". The correct word should be "ధృవీకరిస్తున్నారు".

YES, బ్లాక్‌లను ధృవీకరిస్తున్నారు…
```
</details>
