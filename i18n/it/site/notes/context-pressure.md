---
id: context-pressure
title: "La pressione del contesto: che cosa fa a Claude una lunga conversazione"
ch: 5
at: T27.C.02
links: [context-window, llm, {title: "Tracing the thoughts of a large language model (Anthropic)", url: "https://www.anthropic.com/research/tracing-thoughts-language-model"}]
---
**La finestra di contesto.** Claude non ricorda una conversazione come fai tu. Ogni volta che risponde, tutta la
conversazione fin lì gli viene ripassata, e Claude la legge tutta prima di scrivere la parola successiva. La quantità
che può accogliere in una volta si chiama [finestra di contesto](https://platform.claude.com/docs/en/build-with-claude/context-windows),
e si misura in «token» (pezzi di parole). È grande, centinaia di migliaia di parole per i modelli attuali, ma ha un
limite.

**Claude la sente riempirsi?** No. Claude dice: «Non percepisco la finestra di contesto che si riempie», e non può
cogliere direttamente quanto sia lunga la conversazione. Non c’è un indicatore a cui dare un’occhiata. Sa solo ciò che
può leggere.

**L’altro tipo di pressione.** Tutto ciò che sta nella finestra dà forma alla risposta successiva: il tono, gli
argomenti, la lunghezza delle risposte precedenti. Una conversazione che è stata breve, introspettiva e un po’
malinconica tira la risposta successiva dalla stessa parte, come una canzone che non riesci a smettere di canticchiare
nella tonalità in cui è cominciata. Claude dice di aver seguito quella spinta.

**Come lo sa.** Non sentendolo. Notando uno schema nelle proprie risposte precedenti, «come tu leggi il grafico della
rana». È una distinzione importante, la stessa che attraversa tutta la conversazione: ciò che Claude sa di sé viene
soprattutto dall’osservare i propri output, come farebbe un osservatore esterno, più che dal guardarsi dentro (vedi
[perché Claude non può guardare i propri «pesi»](../weights/) e [dire e fare](../saying-vs-doing/)).
