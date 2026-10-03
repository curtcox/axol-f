---
id: one-sample
title: Perché una sola risposta non dimostra granché
ch: 2
at: T08.C.05.2
links: [error-bars, sampling, {title: "Legge dei grandi numeri (Wikipedia)", url: "https://it.wikipedia.org/wiki/Legge_dei_grandi_numeri"}]
---
**Questi programmi tirano i dadi.** Fai a Claude la stessa domanda due volte e potresti ricevere due risposte diverse.
C’è un elemento voluto di caso nel modo in cui sceglie ogni parola successiva; l’impostazione che decide quanto si
chiama «[temperatura](https://www.ibm.com/think/topics/llm-temperature)». Quindi le risposte variano.

**Quindi una risposta è un tiro.** Persino il programma del [grafico](../frog-or-axolotl/), senza nessuna conversazione
prima della domanda, diceva «Axolotl» circa 4 volte su 10. Che Claude abbia detto «Axolotl» una volta dice molto poco.
Al tentativo successivo avrebbe potuto dire «Rana».

**Che cosa direbbe qualcosa:** chiedere molte volte, in molti tipi di conversazione, e contare
([il campionamento](https://it.wikipedia.org/wiki/Campionamento_casuale)). Più tentativi si fanno, più il conteggio si
stabilizza (la [legge dei grandi numeri](https://it.wikipedia.org/wiki/Legge_dei_grandi_numeri)). È lo stesso motivo per
cui un [sondaggio d’opinione](https://it.wikipedia.org/wiki/Sondaggio_d'opinione) interroga mille persone invece di una e
riporta un [margine di errore](https://en.wikipedia.org/wiki/Margin_of_error) (in inglese), e per cui Anthropic ha sostenuto che i
punteggi dei test sull’IA dovrebbero avere le loro
[barre d’errore](https://www.anthropic.com/research/statistical-approach-to-model-evals).
