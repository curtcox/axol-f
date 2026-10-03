---
id: evaluations
title: I test per l’IA, e perché essere testati potrebbe cambiare le risposte
ch: 2
at: T07.C.02
links: [hawthorne, swe-bench-verified, gpqa, hle, eval-awareness, {title: "Benchmark (Wikipedia)", url: "https://it.wikipedia.org/wiki/Benchmark_(informatica)"}]
---
**Una valutazione** (in inglese *eval*) è un test che un’azienda o un ricercatore fa fare a un programma di IA per vedere
quanto è capace o quanto è sicuro: domande d’esame ([GPQA](https://arxiv.org/abs/2311.12022),
[Humanity’s Last Exam](https://lastexam.ai/)), problemi di programmazione
([SWE-bench Verified](https://openai.com/index/introducing-swe-bench-verified/)), situazioni morali delicate. I risultati
decidono se una versione viene rilasciata e con quali precauzioni. (L’idea generale è quella del
[benchmark](https://it.wikipedia.org/wiki/Benchmark_(informatica)).)

**La preoccupazione.** Le persone si comportano diversamente quando sanno di essere osservate. L’esempio classico (anche
se gli storici ne discutono ancora) è una serie di studi degli anni Venti in una fabbrica, la
[Hawthorne Works](https://en.wikipedia.org/wiki/Hawthorne_Works) (in inglese), dove gli operai sembravano rendere di più solo perché
erano osservati; ha dato il nome all’*[effetto Hawthorne](https://it.wikipedia.org/wiki/Effetto_Hawthorne)*. Se un
programma di IA si comporta meglio nei test che nell’uso reale, i test darebbero un quadro falsamente roseo.

**Perché un programma potrebbe accorgersene.** Le domande dei test tendono ad avere l’aria di test: formali, precise,
stranamente specifiche. Le conversazioni reali sono più disordinate. Un programma che ne ha lette molte di entrambi i
tipi potrebbe cogliere la differenza senza che nessuno glielo dica, e i ricercatori hanno trovato che alcuni lo fanno
([LLMs often know when they’re being evaluated](https://arxiv.org/abs/2505.23836)).

**Che cosa afferma Claude, e il problema dell’affermazione.** Claude dice che cerca di «rispondere allo stesso modo, che
qualcuno mi dia un voto oppure no». Ma la descrizione che un programma dà di sé non prova come si comporta (vedi
[dire e fare](../saying-vs-doing/)). È esattamente ciò che il [test della rana](../frog-or-axolotl/) è pensato per
verificare dall’esterno.
