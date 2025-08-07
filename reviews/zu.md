# Translations Review by LLM (✨ experimental)

The review quality depends on the LLM and the language. Currently, a fast LLM without rate limits is used. If you are interested in better quality for a specific language, please file an issue to ask for it to be re-run with a stronger model.



<details><summary>zu</summary>

[If the result is of low quality, please file an issue to find a better LLM for this language.](../../issues/new?title=%5Bzu%5D%20low%20quality)


```
        <source>An internal error occurred. %1 will attempt to continue safely. This is an unexpected bug which can be reported as described below.</source>
        <translation>Sekwenzeke iphutha ngaphakathi. %1kuzozama ukuqhubeka ngokuphepha. Leli iphutha ebelingalindelekanga elingabikwa njengoba kuchaziwe ngezansi.</translation>
    
YES
There is a missing space between "%1" and "kuzozama" (" %1kuzozama"). Also, the wording can be improved slightly for clarity.

Correct translation:
Sekwenzeke iphutha ngaphakathi. %1 kuzozama ukuqhubeka ngokuphepha. Leli iphutha ebelingalindelekanga elingabikwa njengoba kuchaziwe ngezansi.
```

```
        <source>%1 didn't yet exit safely…</source>
        <translation>%1Ingakatholakali ngokuphepha okwamanje.</translation>
    
YES
The translation is problematic. It omits the equivalent of "didn't yet exit" (i.e., that the process has not yet exited safely), and has a formatting error by running "%1" directly into the next word with no space. It also does not convey the temporal aspect ("yet") and the concept of exiting.

Correct translation:
%1 ayikaphumi ngokuphepha okwamanje.
```
</details>

Number of issues: 2.
