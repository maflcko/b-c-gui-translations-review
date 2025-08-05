# Translations Review by LLM (✨ experimental)

The review quality depends on the LLM and the language. Currently, a fast LLM without rate limits is used. If you are interested in better quality for a specific language, please file an issue to ask for it to be re-run with a stronger model.



<details><summary>zu</summary>

[If the result is of low quality, please file an issue to find a better LLM for this language.](../../issues/new?title=%5Bzu%5D%20low%20quality)


```
        <source>An internal error occurred. %1 will attempt to continue safely. This is an unexpected bug which can be reported as described below.</source>
        <translation>Sekwenzeke iphutha ngaphakathi. %1kuzozama ukuqhubeka ngokuphepha. Leli iphutha ebelingalindelekanga elingabikwa njengoba kuchaziwe ngezansi.</translation>
    
YES
There is a spacing error: "%1kuzozama" should be "%1 kuzozama" (missing space between "%1" and "kuzozama").

Correct translation:
Sekwenzeke iphutha ngaphakathi. %1 kuzozama ukuqhubeka ngokuphepha. Leli iphutha ebelingalindelekanga elingabikwa njengoba kuchaziwe ngezansi.
```

```
        <source>%1 didn't yet exit safely…</source>
        <translation>%1Ingakatholakali ngokuphepha okwamanje.</translation>
    
YES
The translation is problematic. The original English text means that "%1 has not yet exited safely", but the Zulu translation "%1Ingakatholakali ngokuphepha okwamanje." translates more like "%1 is not yet available safely at the moment," which changes the meaning. Also, there is a missing space after %1.

Correct translation:
%1 ayikaphumi ngokuphepha okwamanje.
```
</details>
