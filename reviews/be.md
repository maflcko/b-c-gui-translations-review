# Translations Review by LLM (✨ experimental)

The review quality depends on the LLM and the language. Currently, a fast LLM without rate limits is used. If you are interested in better quality for a specific language, please file an issue to ask for it to be re-run with a stronger model.



<details><summary>be</summary>

[If the result is of low quality, please file an issue to find a better LLM for this language.](../../issues/new?title=%5Bbe%5D%20low%20quality)


```
        <source>This operation needs your wallet passphrase to unlock the wallet.</source>
        <translation>Гэтая аперацыя патрабуе кодавую фразу, каб рзблакаваць гаманец.</translation>
    
YES
There is a typo in the word "разблакаваць" (should be "разблакаваць" instead of "рзблакаваць"). The rest of the sentence is generally correct, but could also be a bit more natural by moving "вашага гаманца" (your wallet) up, to match "your wallet passphrase." However, the major issue is the typo.

Correct translation:
Гэтая аперацыя патрабуе вашую кодавую фразу, каб разблакаваць гаманец.
```

```
        <source>Sign messages with your Bitcoin addresses to prove you own them</source>
        <translation>Падпісаць паведамленне з дапамогай Біткойн-адраса каб даказаць, што яно належыць вам</translation>
    
YES
The Belarusian translation does not precisely capture the plurality ("addresses") present in the source and slightly shifts the meaning ("даказаць, што яно належыць вам" — "to prove that it belongs to you", with "яно" referring to the message rather than the address). Also, "паведамленне" is singular, while the source says "messages". Additionally, there should be a comma before "каб".

Correct translation:
Падпісвайце паведамленні з вашымі Біткойн-адрасамі, каб даказаць, што яны належаць вам
```

```
        <source>Verify messages to ensure they were signed with specified Bitcoin addresses</source>
        <translation>Спраўдзіць паведамленне з дапамогай Біткойн-адраса каб даказаць, што яно належыць вам</translation>
    
YES
The translation deviates from the source meaning and adds extra meaning ("каб даказаць, што яно належыць вам" – "to prove that it belongs to you"), which is not in the original. It also translates "messages" singularly ("паведамленне" instead of "паведамленні"). This is inaccurate and could be misleading.

Correct translation:
Правярайце паведамленні, каб пераканацца, што яны былі падпісаны указанымі Біткойн-адрасамі
```

```
        <source>Request payments (generates QR codes and bitcoin: URIs)</source>
        <translation>Запатрабаваць плацёж (генеруецца QR-код для біткойн URI)</translation>
    
YES
The translation is mostly accurate but has a minor grammatical issue and loses the plurality and completeness of the original phrase "generates QR codes and bitcoin: URIs" (multiple codes and multiple URIs). Also, the passive construction "генеруецца" does not preserve the active sense of "generates". 

Correct translation:
Запатрабаваць плацяжы (генеруе QR-коды і bitcoin: URI)
```

```
        <source>%1 behind</source>
        <translation>%1 таму</translation>
    
YES
The translation '%1 таму' is not accurate for the context in Bitcoin, where "%1 behind" typically refers to being a certain number of blocks or time units behind the network. '%1 таму' means '%1 ago', which can be confusing or incorrect here.

Correct translation:
%1 адстае

This translates to "%1 behind" in Belarusian and preserves the intended meaning.
```

```
        <source>Sent transaction</source>
        <translation>Дасланыя транзакцыі</translation>
    
YES
The translation "Дасланыя транзакцыі" means "Sent transactions" (plural), while the source "Sent transaction" is singular. Therefore, it's not fully accurate.

Correct translation:
Дасланая транзакцыя
```

```
        <source>Incoming transaction</source>
        <translation>Прынятыя транзакцыі</translation>
    
YES
The translation "Прынятыя транзакцыі" means "Received transactions" (plural), while the source "Incoming transaction" refers to a single transaction. The translation should reflect the singular form.

Correct translation:
Уваходная транзакцыя
```

```
        <source>Received with label</source>
        <translation>Прыняць праз метку</translation>
    
YES
The translation "Прыняць праз метку" is incorrect. The English phrase "Received with label" refers to an amount or transaction that was received, associated with a label (tag/description). The given translation means "Accept through label," which is inaccurate in this context.

Correct translation:
Атрымана з меткай
```

```
        <source>Transaction ID</source>
        <translation>ID</translation>
    
YES  
The translation omits the word "Transaction", which is important context. It just says "ID", which is too generic and could be confusing.

Correct translation:
Ідэнтыфікатар транзакцыі
```
</details>

Number of issues: 9.
