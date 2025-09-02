# Translations Review by LLM (✨ experimental)

The review quality depends on the LLM and the language. To report LLM shortcomings for a specific language, please file an issue. It may be possible to re-run with a stronger model.



<details><summary>be</summary>

[If the result is outdated or of low quality, please file an issue to request and updated run for this language.](../../issues/new?title=%5Bbe%5D%20request)


<!-- cache_translation_check_be_0da0cb0cfb19c5c5651bfc193b78ffc1b363d51724c3b73dae005e82bc71198b -->
```
        <source>&amp;New</source>
        <translation>Новы</translation>
    
ERR
The translation omits the ampersand (&), which is necessary to indicate the shortcut key in UI contexts. It should appear exactly once, as in the source.

Correct translation:
&Новы
```

<!-- cache_translation_check_be_8333d19f12c733e4eb2b528f7c84990fc413109e47441706a04a54b5a28ccb6b -->
```
        <source>&amp;Export</source>
        <translation>Экспарт</translation>
    
ERR
The translation omits the ampersand (&), which is needed to indicate the shortcut key, just as in the source.

Correct translation:
&Экспарт
or
Э&кспарт

(The ampersand should appear exactly once in the translation, at a logical keyboard shortcut position.)
```

<!-- cache_translation_check_be_03ca28554d4bd5e6981e559979d6b54b2d2a6454baca3a20989ab18cf2e0d715 -->
```
        <source>This operation needs your wallet passphrase to unlock the wallet.</source>
        <translation>Гэтая аперацыя патрабуе кодавую фразу, каб рзблакаваць гаманец.</translation>
    
ERR
There is a typo in the word "разблакаваць" (should be "разблакаваць" instead of "рзблакаваць"). The rest of the sentence is generally correct, but could also be a bit more natural by moving "вашага гаманца" (your wallet) up, to match "your wallet passphrase." However, the major issue is the typo.

Correct translation:
Гэтая аперацыя патрабуе вашую кодавую фразу, каб разблакаваць гаманец.
```

<!-- cache_translation_check_be_ce931b552fcf97d09ab2fef157142633de2744c597b29a184cd19cdb3f457fe3 -->
```
        <source>&amp;Overview</source>
        <translation>Агляд</translation>
    
ERR
The translation omits the ampersand (&), which is used to indicate a keyboard shortcut (accelerator key) in UI contexts. It should be present once in the translation as well.

Correct translation:
&Агляд

or, if another character is intended as a shortcut:
А&гляд

(but the ampersand must appear exactly once)
```

<!-- cache_translation_check_be_06960a8482d47e158b6e38aa797a862c864300fa78657fe55e56335265042db2 -->
```
        <source>&amp;Transactions</source>
        <translation>Транзакцыі</translation>
    
ERR
The translation "Транзакцыі" omits the ampersand (&), which indicates the shortcut key in the menu label. The ampersand should be included somewhere in the translation, as in "&Транзакцыі".

Correct translation:
&Транзакцыі
```

<!-- cache_translation_check_be_4f5290d95a4eee1b881d1b6cfc82f34e06d12fa2dea0a1a5f7bf04134a3a764b -->
```
        <source>Sign messages with your Bitcoin addresses to prove you own them</source>
        <translation>Падпісаць паведамленне з дапамогай Біткойн-адраса каб даказаць, што яно належыць вам</translation>
    
ERR
The Belarusian translation does not precisely capture the plurality ("addresses") present in the source and slightly shifts the meaning ("даказаць, што яно належыць вам" — "to prove that it belongs to you", with "яно" referring to the message rather than the address). Also, "паведамленне" is singular, while the source says "messages". Additionally, there should be a comma before "каб".

Correct translation:
Падпісвайце паведамленні з вашымі Біткойн-адрасамі, каб даказаць, што яны належаць вам
```

<!-- cache_translation_check_be_af3b3738a5e8ea9eb7cc8627667b7dbf33152bb14ac6df59cbe42d71c9ec7b09 -->
```
        <source>Verify messages to ensure they were signed with specified Bitcoin addresses</source>
        <translation>Спраўдзіць паведамленне з дапамогай Біткойн-адраса каб даказаць, што яно належыць вам</translation>
    
ERR
The translation deviates from the source meaning and adds extra meaning ("каб даказаць, што яно належыць вам" – "to prove that it belongs to you"), which is not in the original. It also translates "messages" singularly ("паведамленне" instead of "паведамленні"). This is inaccurate and could be misleading.

Correct translation:
Правярайце паведамленні, каб пераканацца, што яны былі падпісаны указанымі Біткойн-адрасамі
```

<!-- cache_translation_check_be_e0704da51d86c4761665b221c2cbf31643b5b133331a2860fad63335505fbc77 -->
```
        <source>&amp;Settings</source>
        <translation>Наладкі</translation>
    
ERR
The translation "Наладкі" is correct for "Settings" in Belarusian, but it is missing the ampersand (&), which is needed to indicate the shortcut key, as present in the source "&Settings".

Correct translation:
&Наладкі
```

<!-- cache_translation_check_be_0979a4f33f14df43f28f4ab2e6f87913ebf8d3711929e492e548ac35e624574c -->
```
        <source>Request payments (generates QR codes and bitcoin: URIs)</source>
        <translation>Запатрабаваць плацёж (генеруецца QR-код для біткойн URI)</translation>
    
ERR
The translation is mostly accurate but has a minor grammatical issue and loses the plurality and completeness of the original phrase "generates QR codes and bitcoin: URIs" (multiple codes and multiple URIs). Also, the passive construction "генеруецца" does not preserve the active sense of "generates". 

Correct translation:
Запатрабаваць плацяжы (генеруе QR-коды і bitcoin: URI)
```

<!-- cache_translation_check_be_395e193cce32b1d317522bc1fb6be88ac4ad92fef1298c9609c0b6b613a14172 -->
```
        <source>%1 behind</source>
        <translation>%1 таму</translation>
    
ERR
The translation '%1 таму' is not accurate for the context in Bitcoin, where "%1 behind" typically refers to being a certain number of blocks or time units behind the network. '%1 таму' means '%1 ago', which can be confusing or incorrect here.

Correct translation:
%1 адстае

This translates to "%1 behind" in Belarusian and preserves the intended meaning.
```

<!-- cache_translation_check_be_a7a461de7c1c11f3e848e17b398992b852961337785db19989b3aafbf2bdb54b -->
```
        <source>Sent transaction</source>
        <translation>Дасланыя транзакцыі</translation>
    
ERR
The translation "Дасланыя транзакцыі" means "Sent transactions" (plural), while the source "Sent transaction" is singular. Therefore, it's not fully accurate.

Correct translation:
Дасланая транзакцыя
```

<!-- cache_translation_check_be_2a8a6a9f6f382f1b225dacdbec9eb15f76f2804e0dd54f746232d695000fd852 -->
```
        <source>Incoming transaction</source>
        <translation>Прынятыя транзакцыі</translation>
    
ERR
The translation "Прынятыя транзакцыі" means "Received transactions" (plural), while the source "Incoming transaction" refers to a single transaction. The translation should reflect the singular form.

Correct translation:
Уваходная транзакцыя
```

<!-- cache_translation_check_be_6aee1b53bd8a4582b57da467083f81129de761bf2884c938ac4df58afba7bf5f -->
```
        <source>Received with label</source>
        <translation>Прыняць праз метку</translation>
    
ERR
The translation "Прыняць праз метку" is incorrect. The English phrase "Received with label" refers to an amount or transaction that was received, associated with a label (tag/description). The given translation means "Accept through label," which is inaccurate in this context.

Correct translation:
Атрымана з меткай
```

<!-- cache_translation_check_be_f7adb760bee59d07f257de32fb2f69be42be5ff32156c9d351c213b7f429bdab -->
```
        <source>&amp;Label</source>
        <translation>Метка</translation>
    
ERR
The ampersand (&) indicating the shortcut key is missing in the translation. It should appear once in the translation as in the source.

Correct translation:
&Метка
```

<!-- cache_translation_check_be_d628ca3b2bded1f21e65d12b6d8dbe7203e8bba9e2acbc622bbea83c8fc79abc -->
```
        <source>&amp;Address</source>
        <translation>Адрас</translation>
    
ERR
The translation omits the '&' which is used to indicate a keyboard shortcut in menu items. It should be preserved and appear exactly once, as in the source.

Correct translation:
&Адрас
```

<!-- cache_translation_check_be_68908adc59ae58e8f3bb1441d181430458f56bd8cd39d036ee4603a4ace9933e -->
```
        <source>W&amp;allet</source>
        <translation>Гаманец</translation>
    
ERR
The English source includes an ampersand (&amp;) to indicate a keyboard shortcut, but the Belarusian translation omits it. The ampersand should appear exactly once in the translation, at the appropriate shortcut position.

Correct translation:
&Гаманец

or (if another character is more appropriate as the shortcut in Belarusian, e.g., "Г&аманец").

But one ampersand must be present.
```

<!-- cache_translation_check_be_c4145840804c67928a4f6f1d6b02273100d224c617f130066d161ba94aa0f08d -->
```
        <source>&amp;Information</source>
        <translation>Інфармацыя</translation>
    
ERR
The translation is missing the ampersand (&), which is used to indicate the shortcut key in menus. It should appear in the translation as well.

Correct translation:
&Інфармацыя
```

<!-- cache_translation_check_be_6809cd2274ea208bd7d33d3e466dbf27bc5a03a57eb521119c998a3ec6bb2afa -->
```
        <source>&amp;Label:</source>
        <translation>Метка:</translation>
    
ERR
The translation omits the ampersand (&), which is used for an access key in menus. It should appear exactly once in the translation, as in the source.

Correct translation:
&Метка:
```

<!-- cache_translation_check_be_213c8e8a4bc5c2531315aabd45d06c6b35bd3dac0457eee713e480f507fc1846 -->
```
        <source>A&amp;mount:</source>
        <translation>Колькасць:</translation>
    
ERR
The shortcut marker "&" is missing in the Belarusian translation, which is used for keyboard accelerators in menus. The translation should preserve it, placed before a suitable letter.

Correct translation:
&Колькасць:
```

<!-- cache_translation_check_be_6809cd2274ea208bd7d33d3e466dbf27bc5a03a57eb521119c998a3ec6bb2afa -->
```
        <source>&amp;Label:</source>
        <translation>Метка:</translation>
    
ERR
The translation omits the ampersand (&), which is used for an access key in menus. It should appear exactly once in the translation, as in the source.

Correct translation:
&Метка:
```

<!-- cache_translation_check_be_6736ed11c8e393e1f0d67e5b0ca2360504ffc7ee46276255c5f3faf47810655e -->
```
        <source>Transaction ID</source>
        <translation>ID</translation>
    
ERR  
The translation omits the word "Transaction", which is important context. It just says "ID", which is too generic and could be confusing.

Correct translation:
Ідэнтыфікатар транзакцыі
```

<!-- cache_translation_check_be_8333d19f12c733e4eb2b528f7c84990fc413109e47441706a04a54b5a28ccb6b -->
```
        <source>&amp;Export</source>
        <translation>Экспарт</translation>
    
ERR
The translation omits the ampersand (&), which is needed to indicate the shortcut key, just as in the source.

Correct translation:
&Экспарт
or
Э&кспарт

(The ampersand should appear exactly once in the translation, at a logical keyboard shortcut position.)
```
</details>

Number of issues: 22.
