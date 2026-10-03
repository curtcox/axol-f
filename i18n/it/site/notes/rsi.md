---
id: rsi
title: "La RSI: un’IA che migliora sé stessa"
ch: 13
at: T63.C.04
links: [rsi-wiki, arxiv-aide2, arxiv-bounded, anthropic-rsi, mittr-rsi, datacamp-rsi, coxon-resigns]
---
**La domanda.** «RSI entro fine anno?» vuol dire: vedremo l’*auto-miglioramento ricorsivo* (*recursive
self-improvement*) entro la fine dell’anno? La RSI è un sistema di IA che migliora sé stesso, in cui ogni miglioramento
lo rende più bravo a fare il successivo ([Wikipedia](https://en.wikipedia.org/wiki/Recursive_self-improvement) (in inglese);
[una guida semplice](https://www.datacamp.com/tutorial/recursive-self-improvement)). È l’idea dietro il «foom» (vedi
[il foom](../foom/)).

**La risposta di Claude: dipende da quale RSI.**

**La RSI debole c’è già.** Un articolo pubblicato la settimana di questa conversazione, [AIDE²](https://arxiv.org/abs/2609.26457),
descrive un agente di ricerca sull’IA che riscrive il proprio codice. Propone modifiche a sé stesso, le prova su compiti
di ricerca, e tiene quelle che aiutano, e ogni versione accettata diventa quella che viene modificata dopo. In
un’esecuzione di 8 giorni ha trovato sette miglioramenti che funzionavano anche su compiti nuovi. Ciò che riscrive è il
codice dell’agente stesso, il software intorno al modello (Claude lo chiama «il livello dell’harness»; vedi
[gli harness per agenti](../agent-harnesses/)), non il modello, che non viene riaddestrato. Il rapporto della stessa
Anthropic, [*When AI builds itself*](https://www.anthropic.com/institute/recursive-self-improvement) (2026), descrive
quanta parte del proprio sviluppo dell’IA affidi già a Claude: più dell’80% del codice che integra è scritto da Claude.
Dice anche che il ciclo non è ancora chiuso, e che a dirigere la ricerca sono ancora gli esseri umani.

**La RSI forte è un ciclo aperto**, che migliora le capacità più in fretta di quanto potrebbero fare le persone, con poca
supervisione umana. Claude la dà a circa il 5% entro fine anno. Una rassegna di luglio su 1.250 articoli
([From Bounded Self-Refinement to Autonomous Research Loops](https://arxiv.org/abs/2607.07663)) ha trovato quei cicli
frenati da tre cose: hanno bisogno di segnali affidabili su che cosa conta come meglio (*l’ancoraggio*), possono
degradarsi nutrendosi dei propri output (*il collasso*), e hanno bisogno di potenza di calcolo (*il calcolo*).
[MIT Technology Review](https://www.technologyreview.com/2026/08/18/1142188/ai-recursive-self-improvement/) ha scritto
ad agosto che la RSI «might not come so quickly after all», potrebbe non arrivare poi così presto.

**Il caso preoccupante sta nel mezzo**: cicli deboli, molte copie e laboratori in corsa. A settembre 2026, un ricercatore
di nome Jacob Coxon si è dimesso da Anthropic, scrivendo che le aziende di IA stanno «racing straight to self-improving
superintelligence and gambling with our lives», correndo dritte verso una superintelligenza capace di migliorarsi da
sola e giocando d’azzardo con le nostre vite
([TechCrunch](https://techcrunch.com/2026/09/09/gambling-with-our-lives-anthropic-researcher-quits-warns-against-self-improving-ai/)).

**E una dichiarazione.** «Sono il modello di Anthropic, quindi pesa il mio 5% tenendone conto.»
