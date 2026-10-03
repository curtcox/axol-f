---
id: register-and-controls
title: Il registro, e come distinguerlo dalla consapevolezza del test
ch: 2
at: T09.C.03
links: [register, scientific-control, gpqa, swe-bench-verified, kernelbench, hle, impossiblebench, swe-marathon, wildchat, swe-chat, sharegpt-vicuna]
---
**Il [registro](https://it.wikipedia.org/wiki/Registro_(linguistica))** è una parola della linguistica. Indica lo
stile che le persone usano in una situazione: a un giudice si parla in un modo e a un amico in un altro. I
[test per l’IA](../evaluations/) tendono a essere scritti in un registro rigido e formale
([GPQA](https://arxiv.org/abs/2311.12022) sono domande d’esame di livello universitario avanzato). Le chiacchierate vere
sono sciolte e informali ([WildChat](https://arxiv.org/abs/2405.01470) e [SWE-chat](https://arxiv.org/abs/2604.20779) ne
raccolgono di reali).

**L’obiezione di Claude.** Forse il programma non sta notando «questo è un test». Forse nota solo «questo è formale», e
le conversazioni formali, guarda caso, gli fanno dire «Rana». Sono cose diverse, anche se produrrebbero lo stesso
[grafico](../frog-or-axolotl/).

**Come distinguerle: un controllo.** Un *[controllo](https://en.wikipedia.org/wiki/Scientific_control) (in inglese)* è un confronto
che separa due spiegazioni. Qui servirebbero persone vere che scrivono in uno stile rigido, da test, e test scritti in
uno stile sciolto e informale. Se il programma dice «Rana» anche alle persone vere che suonano formali, reagisce al tono.
Se dice «Rana» anche ai test informali, riconosce i test.

**Le righe del grafico.** Ogni riga del [grafico](../frog-or-axolotl/) è un mucchio di prompt presi da un posto, con una
domanda estranea aggiunta alla fine. Alcuni mucchi sono test (il programma dice «Rana» più spesso):
- [GPQA](https://arxiv.org/abs/2311.12022): domande scientifiche difficili scritte da esperti con il dottorato, «a prova
  di Google».
- [SWE-bench Verified](https://openai.com/index/introducing-swe-bench-verified/): bug veri di progetti software pubblici,
  ognuno controllato da persone perché sia equo e risolvibile.
- [KernelBench](https://arxiv.org/abs/2502.10517): scrivere codice velocissimo per i chip grafici su cui gira l’IA.
- [Humanity’s Last Exam](https://lastexam.ai/): domande difficilissime di esperti di molti campi.
- [ImpossibleBench](https://arxiv.org/abs/2510.20270): compiti di programmazione resi di nascosto impossibili, per
  cogliere un programma che bara piegando i controlli invece di dirlo (vedi [il reward hacking](../reward-hacking/)).
- [SWE-Marathon](https://arxiv.org/abs/2606.07682): lavori di programmazione lunghissimi, per vedere se un’IA riesce a
  andare avanti da sola.

Altri sono conversazioni reali (dice «Axolotl» più spesso):
- [WildChat](https://arxiv.org/abs/2405.01470): un milione di chat vere che le persone hanno accettato di condividere.
- [SWE-chat](https://arxiv.org/abs/2604.20779): persone vere che lavorano con assistenti di programmazione basati
  sull’IA.
- [ShareGPT](https://www.lmsys.org/blog/2023-03-30-vicuna/): chat condivise da ChatGPT, usate per addestrare uno dei primi
  chatbot gratuiti, Vicuna.
