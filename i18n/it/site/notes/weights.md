---
id: weights
title: Perché Claude non può guardare i propri «pesi»
ch: 2
at: T08.C.03
links: [introspection, tracing-thoughts, monosemanticity, {title: "Rete neurale (Wikipedia)", url: "https://it.wikipedia.org/wiki/Rete_neurale_artificiale"}, {title: "Introspezione (Wikipedia)", url: "https://it.wikipedia.org/wiki/Introspezione"}]
---
**I pesi, in parole semplici.** Dentro un programma come Claude c’è un’immensa tabella di numeri, miliardi, chiamati
*pesi* (sono le forze delle connessioni in una [rete neurale](https://it.wikipedia.org/wiki/Rete_neurale_artificiale),
ispirata alla lontana ai [neuroni](https://en.wikipedia.org/wiki/Artificial_neuron) (in inglese)). Sono stati aggiustati, un
pochino alla volta, mentre il programma studiava testi, finché non ha cominciato a scrivere bene. Quei numeri *sono* le
conoscenze e le abitudini del programma. Nessuno li ha scritti a mano, e nessuno può leggerli come un libro.

**«Non posso ispezionare i miei pesi.»** Mentre parla, Claude non può guardare quei numeri. È un po’ come una persona
che non può vedere i propri neuroni: puoi dire agli altri che cosa *pensi* di stare facendo
([introspezione](https://it.wikipedia.org/wiki/Introspezione)), ma non puoi controllare i fili. Quindi quando Claude
dice perché ha fatto qualcosa, quella spiegazione può corrispondere o no a ciò che è successo davvero dentro (vedi
[dire e fare](../saying-vs-doing/)).

**Qualcuno può guardarci?** I ricercatori sì, con strumenti speciali, e stanno imparando a trovare in quei numeri
schemi che corrispondono a idee. In una dimostrazione famosa, Anthropic ha trovato lo schema del Golden Gate Bridge e
l’ha alzato, producendo «[Golden Gate Claude](https://www.anthropic.com/news/golden-gate-claude)», che infilava il ponte
in ogni risposta. Lo stesso lavoro ha trovato schemi legati a cose come l’inganno
([Scaling Monosemanticity](https://transformer-circuits.pub/2024/scaling-monosemanticity/)), e lavori successivi
seguono come il programma affronta un problema passo per passo
([Tracing the thoughts of a language model](https://www.anthropic.com/research/tracing-thoughts-language-model)).
Questo campo si chiama *[interpretabilità](https://en.wikipedia.org/wiki/Mechanistic_interpretability) (in inglese)*. È agli
inizi, ed è uno dei modi principali con cui si spera di verificare che cosa fanno davvero questi programmi.

**Alcuni programmi riescono ad accorgersi un po’.** Ricercatori di Anthropic hanno trovato che Claude a volte riesce a
cogliere un’idea piantata artificialmente nella propria elaborazione, ma solo a volte
([Emergent introspective awareness](https://transformer-circuits.pub/2025/introspection/index.html)). La sua
conoscenza di sé è reale ma inaffidabile.
