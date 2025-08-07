# Translations Review by LLM (✨ experimental)

The review quality depends on the LLM and the language. Currently, a fast LLM without rate limits is used. If you are interested in better quality for a specific language, please file an issue to ask for it to be re-run with a stronger model.



<details><summary>kk</summary>

[If the result is of low quality, please file an issue to find a better LLM for this language.](../../issues/new?title=%5Bkk%5D%20low%20quality)


```
        <source>Right-click to edit address or label</source>
        <translation>Мекенжай немесе белгі өңдеу үшін оң клик</translation>
    
YES
The translation is not fully grammatically correct and is a bit awkward in Kazakh. "оң клик" is a direct transliteration of "right click" and is understood informally, but a more natural/formal phrasing would be "тінтуірдің оң жағымен басыңыз" ("click the right mouse button"). Also, the structure should better reflect the instruction to right-click in order to edit the address or label.

Correct translation:
Мекенжайды немесе белгіні өңдеу үшін тінтуірдің оң жақ түймешігін басыңыз
```

```
        <source>Wallet encryption failed due to an internal error. Your wallet was not encrypted.</source>
        <translation>Әмиян ішкі қате кесірінен шифланбады.</translation>
    
YES
The translation omits information from the source. The source mentions both the failure of wallet encryption due to an internal error and explicitly states "Your wallet was not encrypted." The translation only communicates that "the wallet was not encrypted due to an internal error" but lacks clarity and omits the repetition from the source, which is important for the user.

Correct translation:
Әмиянды шифрлау ішкі қате салдарынан сәтсіз аяқталды. Әмияныңыз шифрланбады.
```

```
        <source>Sign messages with your Bitcoin addresses to prove you own them</source>
        <translation>Хатқа Bitcoin мекенжайларын қосып, олар сізге тиесілі екенін дәлелдеу</translation>
    
YES
The translation is inaccurate. The source refers to "signing messages" with your Bitcoin addresses to prove ownership, but the translation says "Қосып" which means "by adding". It does not convey the meaning of cryptographically signing messages.

Correct translation:
Bitcoin мекенжайларыңызбен хабарламаларды қол қойып, олар сізге тиесілі екенін дәлелдеңіз
```

```
        <source>Verify messages to ensure they were signed with specified Bitcoin addresses</source>
        <translation>Хат тексеріп, берілген Bitcoin мекенжайлары қосылғанына көз жеткізу</translation>
    
YES
The Kazakh translation is inaccurate. The original says "Verify messages to ensure they were signed with specified Bitcoin addresses." The translation instead says "Check the message and make sure the specified Bitcoin addresses are added," which changes the meaning.

Correct translation:
Хабарламаларды берілген Bitcoin мекенжайларымен қол қойылғанына көз жеткізу үшін тексеріңіз
```

```
        <source>Request payments (generates QR codes and bitcoin: URIs)</source>
        <translation>Төлем талап ету (QR кодтары мен биткоин құрады: URI)</translation>
    
YES
The translation is somewhat inaccurate in both syntax and meaning. The phrase "биткоин құрады: URI" is unnatural and ambiguous in Kazakh, as it seems to suggest "creates bitcoin: URI" but the ordering and morphology are incorrect. Also, the phrase "QR кодтары мен биткоин құрады: URI" doesn't clearly convey that both QR codes and bitcoin: URIs are generated.

Correct translation:
Төлем талап ету (QR кодтарын және bitcoin: URI жасайды)
```
</details>

Number of issues: 5.
