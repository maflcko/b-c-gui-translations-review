# Translations Review by LLM (✨ experimental)

The review quality depends on the LLM and the language. Currently, a fast LLM without rate limits is used. If you are interested in better quality for a specific language, please file an issue to ask for it to be re-run with a stronger model.



<details><summary>be</summary>

[If the result is of low quality, please file an issue to find a better LLM for this language.](../../issues/new?title=%5Bbe%5D%20low%20quality)


```
        <source>This operation needs your wallet passphrase to unlock the wallet.</source>
        <translation>Гэтая аперацыя патрабуе кодавую фразу, каб рзблакаваць гаманец.</translation>
    
YES
There is a typo in the translation: "рзблакаваць" should be "разблакаваць". Also, to be fully accurate and natural in Belarusian, "патрэбна" is preferable over "патрабуе", but "патрабуе" is still understandable. For clarity, the direct translation should also refer to "вашага гаманца" ("your wallet") for completeness, since the English mentions "your wallet passphrase".

Correct translation:
Гэтая аперацыя патрабуе вашу кодавую фразу для разблакавання гаманца.
```

```
        <source>Sign messages with your Bitcoin addresses to prove you own them</source>
        <translation>Падпісаць паведамленне з дапамогай Біткойн-адраса каб даказаць, што яно належыць вам</translation>
    
YES
The translation inaccurately uses the singular form "паведамленне" (message) instead of the plural "паведамленні" (messages) from the source. Also, it says "што яно належыць вам" (that it belongs to you), which refers to "message" (but in reality, the address/ownership is being proven), not the address. The wording could be clearer and more accurate.

Correct translation:
Падпісвайце паведамленні сваімі Біткойн-адрасамі, каб даказаць, што яны належаць вам

OR

Падпісвайце паведамленні сваімі Біткойн-адрасамі, каб даказаць, што вы імі валодаеце
```

```
        <source>Verify messages to ensure they were signed with specified Bitcoin addresses</source>
        <translation>Спраўдзіць паведамленне з дапамогай Біткойн-адраса каб даказаць, што яно належыць вам</translation>
    
YES
The translation is inaccurate. The source refers to verifying messages to ensure they were signed with specified Bitcoin addresses, not about proving ownership of a message. Additionally, "message" should be plural, and the purpose (ensuring they were signed with specified Bitcoin addresses) should be kept.

Correct translation:
Правярайце паведамленні, каб пераканацца, што яны былі падпісаны пазначанымі Біткойн-адрасамі
```

```
        <source>Request payments (generates QR codes and bitcoin: URIs)</source>
        <translation>Запатрабаваць плацёж (генеруецца QR-код для біткойн URI)</translation>
    
YES  
The translation is mostly correct, but the Belarusian translation uses "генеруецца" (is generated) in the passive voice, while the English uses the active "generates" and also mentions both "QR codes" (plural) and "bitcoin: URIs" (plural). The translation only refers to generating a single QR-code for "біткойн URI" (singular), missing the plural and the fact that it generates both QR-codes and URIs, not just one QR code for a URI.

Correct translation:  
Запатрабаваць плацяжы (генеруе QR-коды і bitcoin: URI)
```

```
        <source>%1 behind</source>
        <translation>%1 таму</translation>
    
YES
The translation "%1 таму" is incorrect. The phrase "%1 behind" in the context of Bitcoin typically means that something is lagging or behind by %1 blocks/units/etc. The word "таму" means "therefore" or "so" in Belarusian, which is not a correct translation of "behind."

Correct translation:
%1 ззаду

Alternatively, if it's about being behind by (e.g., blocks), a more contextually accurate translation would be:
%1 адстае

So the most neutral would be:
%1 ззаду
```

```
        <source>Transactions after this will not yet be visible.</source>
        <translation>Транзакцыи пасля гэтай не будуць бачныя.</translation>
    
YES
The translation is problematic: there is a typo in the word "Транзакцыи" (should be "Транзакцыі"), and "після гэтай" is inaccurate; more accurate would be "пасля гэтага". Also, "will not yet be visible" translates better as "яшчэ не будуць бачныя" to reflect "not yet". 

Correct translation:
Транзакцыі пасля гэтага яшчэ не будуць бачныя.
```

```
        <source>Sent transaction</source>
        <translation>Дасланыя транзакцыі</translation>
    
YES
The translation "Дасланыя транзакцыі" means "Sent transactions" (plural) in Belarusian, while the source is "Sent transaction" (singular). The translation should match the singular form.

Correct translation:
Дасланая транзакцыя
```

```
        <source>Incoming transaction</source>
        <translation>Прынятыя транзакцыі</translation>
    
YES
The translation uses the plural form "Прынятыя транзакцыі" ("Accepted transactions" or "Received transactions"), while the source is singular: "Incoming transaction." The translation should mirror the singular.

Correct translation:
Прыходная транзакцыя
```

```
        <source>Received with label</source>
        <translation>Прыняць праз метку</translation>
    
YES  
The translation "Прыняць праз метку" is incorrect. The English phrase "Received with label" refers to items that have been received and are associated with a specific label, often seen in transaction lists. The translation "Прыняць праз метку" reads as "Receive via label", which does not convey the intended meaning. The correct translation should better reflect the idea of items received that have a label.

Correct translation:  
Атрымана з меткай
```

```
        <source>Transaction ID</source>
        <translation>ID</translation>
    
YES
The translation is incomplete; "Transaction ID" should be translated fully into Belarusian, not just "ID". 

Correct translation:
Ідэнтыфікатар транзакцыі
```

```
        <source>Error initializing wallet database environment %s!</source>
        <translation>Памалка ініцыялізацыі асяроддзя базы звестак гаманца %s!</translation>
    
YES
The translation contains an error: "Памалка" is a typo and should be "Памылка", which means "Error" in Belarusian. The rest of the translation is accurate and retains the format specifier %s.

Correct translation:
Памылка ініцыялізацыі асяроддзя базы звестак гаманца %s!
```
</details>
