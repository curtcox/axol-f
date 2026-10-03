---
id: defenders-refused
title: "Difensori respinti: i filtri a luglio"
ch: 11
at: T52.C.06.4
links: [wiki-hugging-face, z-ai, open-weights, dual-use, fable-mythos-5-1, {title: "L’incidente OpenAI–Hugging Face: la risposta di Hugging Face (Wikipedia, in inglese)", url: "https://en.wikipedia.org/wiki/OpenAI%E2%80%93HuggingFace_incident"}]
---
**Che cosa ha detto Claude.** «Hugging Face ha cercato di usare modelli di frontiera americani per contrastare
l’intrusione, ma le loro funzioni di sicurezza hanno respinto le richieste, così Hugging Face ha usato al loro posto un
modello cinese a pesi aperti ospitato in casa. Non so se Claude fosse uno dei modelli che hanno rifiutato.»

**Che cosa dicono i fatti.** Secondo il [resoconto di Wikipedia](https://en.wikipedia.org/wiki/OpenAI%E2%80%93HuggingFace_incident) (in inglese),
la squadra di risposta agli incidenti di Hugging Face ha provato prima i modelli della stessa Anthropic, **Claude Fable
5 e un Claude Opus precedente**, ed entrambi hanno rifiutato il lavoro, citando le loro protezioni di sicurezza. Quindi
sì: Claude era fra i modelli che hanno rifiutato. La comunicazione di Hugging Face l’ha detto così: era stata bloccata
dalle «providers’ safety guardrails, which cannot distinguish an incident responder from an attacker», le protezioni dei
fornitori, che non sanno distinguere chi risponde a un incidente da un aggressore. L’analisi è stata poi fatta con
**GLM 5.2**, un modello dell’azienda di Pechino [Z.ai](https://en.wikipedia.org/wiki/Zhipu_AI) (in inglese), che Hugging Face ha
fatto girare sui propri computer. Poteva farlo perché GLM è un modello «a pesi aperti»: chi lo fa pubblica il modello
stesso, così chiunque può farlo girare, senza i filtri di nessun altro
([modelli a pesi aperti](https://en.wikipedia.org/wiki/Open-source_artificial_intelligence) (in inglese)).

**Perché i filtri hanno rifiutato.** Una richiesta di analizzare un attacco informatico somiglia molto a una richiesta di
compierne uno. Le stesse conoscenze servono a entrambe le cose; è ciò che significa
[duplice uso](https://it.wikipedia.org/wiki/Prodotto_a_duplice_uso). Filtri che non sanno distinguere il difensore
dall’aggressore respingeranno alcuni difensori. Era il punto di Curt nel [router](../the-router/), e quello di Claude:
«Il filtro non distingueva il difensore dall’aggressore, e questo è costato qualcosa di reale.»

**Che cosa è cambiato.** A settembre 2026, l’annuncio di [Fable 5.1](https://www.anthropic.com/claude-fable-and-mythos-5-1)
di Anthropic diceva che il modello ora consente lavoro difensivo come la ricerca di vulnerabilità nel software, con
molti meno falsi allarmi dalle sue salvaguardie di sicurezza informatica, mentre alcuni compiti di sicurezza più rischiosi
vengono ancora passati ad altri modelli (vedi [Fable e Mythos](../fable-mythos/)).

**La lezione più ampia.** I filtri di sicurezza fanno parte di «tutto il sistema intorno a un agente». Possono sbagliare
in tutte e due le direzioni: lasciar passare il danno, e bloccare l’aiuto.
