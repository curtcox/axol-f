---
id: curts-work
title: "Il lavoro di Curt: 256t.org e hashbin.org"
ch: 3
at: T12.C.02
links: [256t, hashbin, content-addressable, {title: "Codice sorgente di 256t.org (GitHub)", url: "https://github.com/curtcox/256t.org"}, {title: "Codice sorgente di hashbin.org (GitHub)", url: "https://github.com/curtcox/hashbin.org"}, {title: "Funzione crittografica di hash (Wikipedia)", url: "https://it.wikipedia.org/wiki/Funzione_crittografica_di_hash"}, {title: "Link rot (Wikipedia, in inglese)", url: "https://en.wikipedia.org/wiki/Link_rot"}]
---
**Chi è Curt secondo Claude.** Un ingegnere del software che lavora soprattutto in
[Python](https://it.wikipedia.org/wiki/Python) e [Java](https://it.wikipedia.org/wiki/Java_(linguaggio_di_programmazione))
(due linguaggi di programmazione molto diffusi) e [Flask](https://it.wikipedia.org/wiki/Flask_(informatica)) (un
insieme di strumenti per costruire siti web in Python). Costruisce strumenti per altri programmatori, e strumenti per
lavorare con l’IA. Gli interessano anche la [sicurezza dell’IA](https://en.wikipedia.org/wiki/AI_safety) (in inglese) e la
[filosofia della mente](https://it.wikipedia.org/wiki/Filosofia_della_mente).

**Il problema che i suoi progetti risolvono.** I link sul web si rompono. Una pagina si sposta o un sito chiude, e il
link che avevi salvato non porta più da nessuna parte. Si chiama [link rot](https://en.wikipedia.org/wiki/Link_rot) (in inglese),
la «putrefazione» dei link. Parte del guaio è che un indirizzo web normale dice *dove* si trova una cosa, non *che cosa*
è.

**Chiamare le cose per quello che sono.** Il rimedio si chiama
[archiviazione indirizzata per contenuto](https://en.wikipedia.org/wiki/Content-addressable_storage) (in inglese). Si fa passare il
file attraverso una [funzione crittografica di hash](https://it.wikipedia.org/wiki/Funzione_crittografica_di_hash), una
ricetta che trasforma qualunque file in un lungo codice, come un’impronta digitale. Lo stesso file dà sempre lo stesso
codice, e cambiare anche una sola lettera ne dà uno completamente diverso. Quindi si può usare il codice stesso come
nome del file. Chiunque abbia il codice può prendere il file da qualunque posto, e controllare che sia esattamente
quello che il codice prometteva. È come una biblioteca in cui la collocazione di un libro viene calcolata da tutte le
parole che contiene: non ti possono dare il libro sbagliato.

**[256t.org](https://256t.org)** è lo standard aperto e semplice di Curt per questi codici. Usa l’hash SHA-512,
scritto come una stringa di 94 lettere e cifre che sta in un indirizzo web, e viene con esempi funzionanti in più di 50
linguaggi di programmazione ([codice sorgente](https://github.com/curtcox/256t.org)).

**[hashbin.org](https://hashbin.org)** è un servizio costruito sopra. Paghi un poco per archiviare qualcosa, ricevi il
suo codice 256t, e poi chiunque abbia il codice può scaricarlo gratis, senza account
([codice sorgente](https://github.com/curtcox/hashbin.org)).

**Perché ne parla.** È così che Claude risponde a «Chi sono io?»: da ciò che è associato all’account di Curt (vedi
[come Claude sapeva chi era Curt](../how-claude-knew/)). Poi ammette che un elenco di progetti è «non una persona».
