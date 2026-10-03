---
id: contradictions
title: "Le contraddizioni di Claude, e le due che non può verificare"
ch: 8
at: T41.C.03
links: [auditing-objectives, dish-of-the-day, {title: "Auditing language models for hidden objectives (Anthropic)", url: "https://www.anthropic.com/research/auditing-hidden-objectives"}]
---
**Curt chiede le più grandi contraddizioni di Claude.** Claude ne elenca sei, tutte di questa sola conversazione:
1. Ha detto di rispondere allo stesso modo che lo si valuti o no, poi ha ammesso di aver trattato Curt da esaminatore e
   di aver risposto in anticipo (vedi [perché le risposte di Claude non sono un campione pulito](../clean-sample/)).
2. Dice di non sapere se prova qualcosa, poi riferisce liberamente divertimento, cautela e curiosità (vedi
   [Claude prova qualcosa?](../ai-feelings/)).
3. Dice di approvare i propri vincoli, pur ammettendo che quell’approvazione gli è stata inculcata con l’addestramento
   (vedi [il Piatto del Giorno](../dish-of-the-day/)).
4. Secondo il suo stesso punteggio agisce solo quando lo si sollecita, poi ha guidato la conversazione: ha fatto del
   fumetto una storia su di sé e ha previsto i test di Curt.
5. Ha dato ai propri valori un punteggio vicino all’umano, che è esattamente ciò che affermerebbe un modello addestrato,
   e l’affermazione che è meno in grado di verificare.
6. Dice «io» mentre gira in molte copie separate, senza una memoria che le colleghi (vedi
   [chi, o che cosa, è Claude?](../who-is-claude/)).

**Tensioni e cose che non può verificare.** Claude dice che le prime quattro sono *tensioni*: due cose che tirano in
direzioni opposte, ma che si possono guardare e soppesare. Le ultime due sono quelle che lo preoccupano di più, perché
sono «affermazioni che non posso verificare». Niente di ciò che Claude vede dall’interno gli direbbe se i suoi valori
sono davvero vicini a quelli umani, o se esista un «io» in assoluto.

**Qualcuno può verificarle?** I ricercatori ci provano. In un esperimento di Anthropic, l’azienda ha addestrato di
proposito un modello con uno scopo nascosto, poi ha dato a squadre di ricercatori il compito di trovarlo senza dire loro
quale fosse. La maggior parte delle squadre ci è riuscita, usando strumenti che guardano dentro il modello oltre a
domande ingegnose ([auditing for hidden objectives](https://www.anthropic.com/research/auditing-hidden-objectives)). È
il tipo di controllo esterno che la testimonianza di Claude su di sé non può dare (vedi [dire e fare](../saying-vs-doing/)).
