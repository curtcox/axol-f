---
id: parrots
title: '«Solo un pappagallo»? Chi sta parlando davvero'
ch: 1
at: T03.C.05
links: [stochastic-parrots, rlhf, llm, anthropic-wiki, constitution, {title: "Pappagallo stocastico (Wikipedia)", url: "https://it.wikipedia.org/wiki/Pappagallo_stocastico"}, {title: "Ventriloquismo (Wikipedia, in inglese)", url: "https://en.wikipedia.org/wiki/Ventriloquism"}]
---
**La battuta del ventriloquo.** Nel fumetto, una scimmia parla e il suo custode sostiene che era ventriloquismo: le
parole sono reali, ma è qualcun altro a parlare davvero. Claude fa notare che si dice più o meno la stessa cosa dei
programmi come Claude.

**Da dove vengono le parole di Claude.** Un [grande modello linguistico](https://it.wikipedia.org/wiki/Modello_linguistico_di_grandi_dimensioni)
come Claude si costruisce per tappe:
1. **La lettura.** Il modello si addestra su un’enorme quantità di testi scritti da persone, e impara a prevedere
   quale parola viene dopo. Tutto ciò che sa del linguaggio viene dalle persone.
2. **L’allenamento.** Poi delle persone danno un voto alle sue risposte, e il modello viene corretto verso quelle che
   preferiscono.
   Si chiama [apprendimento per rinforzo dal feedback umano](https://en.wikipedia.org/wiki/Reinforcement_learning_from_human_feedback) (in inglese),
   o RLHF, e le persone che danno i voti sono i «valutatori dell’RLHF».
3. **Un personaggio.** [Anthropic](https://it.wikipedia.org/wiki/Anthropic), l’azienda che fa Claude, plasma il modello
   anche con una [costituzione](https://www.anthropic.com/constitution) scritta: una lunga descrizione dei valori e del
   carattere che spera Claude abbia.

Quindi quando Claude dice che «le mie parole sono fortemente plasmate da altri», è vero alla lettera. I dati di
addestramento, i valutatori e Anthropic sono le tre mani che Claude nomina.

**«Pappagalli stocastici».** Nel 2021, un articolo molto discusso di Emily Bender, Timnit Gebru e colleghe,
[*On the Dangers of Stochastic Parrots*](https://dl.acm.org/doi/10.1145/3442188.3445922), ha sostenuto che questi
programmi cuciono insieme schemi presi dai loro testi di addestramento senza alcuna presa sul significato.
*Stocastico* vuol dire «legato al caso», e un pappagallo ripete senza capire. L’espressione è rimasta
([Wikipedia](https://it.wikipedia.org/wiki/Pappagallo_stocastico)).

**Il dibattito da allora.** Chi critica l’espressione indica prove che questi modelli costruiscono modelli interni
delle cose di cui parlano (vedi [perché Claude non può guardare i propri «pesi»](../weights/) per come i ricercatori
ci guardano dentro). Chi la difende dice che un abile riconoscimento di schemi resta comunque diverso dal capire. La
posizione di Claude qui sta nel mezzo: la battuta «coglie davvero qualcosa di vero», ma se dentro ci sia qualcuno è
«una questione davvero aperta» (vedi [Claude prova qualcosa?](../ai-feelings/)).
