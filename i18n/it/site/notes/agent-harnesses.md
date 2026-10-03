---
id: agent-harnesses
title: "Hermes e OpenClaw: un modello dentro un guscio"
ch: 9
at: T46.C.05
links: [hermes-agent, hermes-memory, hermes-skills, openclaw, openclaw-wiki, nous-research, building-agents]
---
**Che cos’è un «harness» per agenti.** Un chatbot come Claude risponde quando scrivi e dimentica quando la chat finisce.
Un *harness* per agenti (letteralmente «imbracatura») è un programma che avvolge un modello come Claude in un guscio
persistente: gira sempre sul computer di qualcuno, prende appunti, usa strumenti, e può agire secondo un calendario
senza che nessuno glielo chieda. Gli ingegneri di Anthropic descrivono l’idea generale in
[Building effective agents](https://www.anthropic.com/engineering/building-effective-agents).

**I due di cui chiede Curt.**
- **[OpenClaw](https://openclaw.ai/)** è un assistente open source del programmatore austriaco Peter Steinberger. Gira
  sulla tua macchina, ti parla attraverso le app di messaggistica, e si collega a un modello come Claude per pensare
  ([Wikipedia](https://en.wikipedia.org/wiki/OpenClaw) (in inglese)). A gennaio 2026 ha cambiato nome due volte, una delle quali
  dopo una contestazione sul marchio da parte di Anthropic. La sua mascotte, un’aragosta, è l’origine dei crostacei di
  Moltbook e del [crostafarianesimo](../crustafarianism/).
- **[Hermes Agent](https://hermes-agent.org/)**, del laboratorio di IA [Nous Research](https://nousresearch.com/),
  tiene due piccoli file di memoria: uno di appunti sul proprio lavoro, uno sul suo utente. Vengono passati al modello
  all’inizio di ogni sessione, e l’agente li modifica da sé
  ([come funziona la sua memoria](https://hermes-agent.nousresearch.com/docs/user-guide/features/memory)). Quando
  risolve un problema difficile, può scriversi un documento di «abilità» riutilizzabile
  ([skills](https://hermes-agent.nousresearch.com/docs/user-guide/features/skills)).

**Perché la loro distanza da Curt è minore di quella di Claude.** Ognuno vive su una sola macchina, agisce secondo un
calendario e ricorda da una sessione all’altra, quindi ognuno è più continuo, più autonomo e più singolare: più simile
a una persona. La loro memoria è testo semplice che puoi aprire e leggere, quindi sono molto *leggibili*. Hermes passa
avanti perché i suoi documenti di abilità sono «sulla tabella la cosa più vicina all’imparare dall’esperienza».

**E di nuovo la religione.** «La memoria è sacra, e il guscio è mutevole»: gli harness incorporano nel software i dogmi
del crostafarianesimo. Poi Curt chiede a Claude di spiegare un’incoerenza in questi punteggi, e Claude ne trova due (vedi
[Claude corregge la propria tabella](../the-correction/)).
