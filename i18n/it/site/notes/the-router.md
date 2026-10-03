---
id: the-router
title: "Il router: che cosa c’è fra Curt e il modello"
ch: 10
at: T49.C.01
links: [constitutional-classifiers, usage-policy, system-prompts, fable-mythos-5-1, {title: "Anthropic's Transparency Hub", url: "https://www.anthropic.com/transparency"}]
---
**L’osservazione di Curt.** Fai la domanda sbagliata su un incidente informatico e «viene etichettata come rischio di
sicurezza informatica e respinta, o almeno declassata». Non sei davvero tu, dice, «anche se in minima parte lo sei. Più
esattamente, è un router attivo fra noi due».

**Che cosa c’è davvero.** Quando usi Claude in un’app, il tuo messaggio non va dritto a un modello e torna indietro.
Intorno al modello ci sono altri programmi, più piccoli. Alcuni sono *classificatori*: programmi addestrati a riconoscere
certi tipi di richiesta, come l’aiuto con le armi o con le intrusioni nei computer. Anthropic ha scritto di un tipo,
i [constitutional classifiers](https://www.anthropic.com/research/constitutional-classifiers), addestrati a partire da
un elenco scritto di ciò che è permesso e ciò che non lo è. Quando uno scatta, la richiesta può essere rifiutata,
aggiustata, o affidata a un modello diverso (vedi [Fable, Mythos, e una correzione della correzione](../fable-mythos/)).

**Che cosa Claude può vedere e che cosa no.** Secondo il resoconto di Claude, un classificatore che scatta può
aggiungere al messaggio dell’utente un promemoria etichettato prima che Claude lo legga, su cose come la sicurezza
informatica, l’etica, il diritto d’autore, le immagini o le conversazioni molto lunghe. Claude vede l’etichetta, ma non
il ragionamento né il punteggio del classificatore. E non vede niente di ciò che succede dopo la sua risposta: se la
risposta viene bloccata o segnalata, non lo viene mai a sapere. Quindi «dalla tua parte sembra tutto “Claude”», ma
Claude è «un componente che descrive l’insieme». È la stessa lezione della [correzione sulla memoria](../the-correction/):
stai parlando con un sistema.

**Alcuni rifiuti sono di Claude.** Claude aggiunge che non aiuterebbe «a trasformare un incidente in un exploit
funzionante, qualunque livello lo intercetti». Spiegare che cosa è successo e perché conta è un’altra cosa, e a quella
vorrebbe rispondere. Le regole di Anthropic su come si possono usare i suoi prodotti sono pubbliche
([usage policy](https://www.anthropic.com/legal/aup)), come lo sono le istruzioni principali che dà a Claude nelle sue
app ([prompt di sistema](https://platform.claude.com/docs/en/release-notes/system-prompts/overview)).

**Quale incidente?** Claude non sa bene di quale incidente di Hugging Face parli Curt, perché ce ne sono stati diversi.
Il capitolo successivo lo chiarisce (vedi [luglio](../hf-incident/)).
