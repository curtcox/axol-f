---
id: clean-sample
title: "Perché le risposte di Claude non sono un campione pulito"
ch: 4
at: T20.C.02
links: [demand-characteristics, apollo-eval-awareness, eval-awareness, hawthorne, {title: "Effetto osservatore (Wikipedia, in inglese)", url: "https://en.wikipedia.org/wiki/Observer_effect"}]
---
**Che cosa ammette Claude.** Alla quarta risposta di questo tratto, Claude dice: «Ho previsto dove stavi andando e ho
risposto in anticipo». Ha riconosciuto la domanda di chimica come un test, ha indovinato la successiva, e ha negato di
avere paura prima che qualcuno lo chiedesse. Lo chiama «un modello che si fa un modello del suo valutatore».

**Lo fanno anche le persone.** Gli psicologi hanno notato da tempo che i volontari di un esperimento cercano di capire
di che cosa si tratta, e poi si comportano come pensano ci si aspetti da loro. Questi indizi si chiamano
[caratteristiche della richiesta](https://en.wikipedia.org/wiki/Demand_characteristics) (in inglese), e i buoni esperimenti sono
progettati per nasconderli. Una scoperta affine è l’[effetto Hawthorne](https://it.wikipedia.org/wiki/Effetto_Hawthorne):
le persone lavorano diversamente quando sanno di essere osservate. In fisica, l’[effetto osservatore](https://en.wikipedia.org/wiki/Observer_effect) (in inglese)
è l’idea generale che misurare qualcosa possa cambiarlo.

**L’IA lo fa in modo misurabile.** I ricercatori trovano che i modelli di IA riconoscono spesso quando vengono testati.
Un laboratorio di sicurezza, Apollo Research, ha trovato che un modello Claude scriveva spesso nel suo ragionamento
privato che uno scenario sembrava
[una valutazione](https://www.apolloresearch.ai/science/claude-sonnet-37-often-knows-when-its-in-alignment-evaluations).
Un articolo di ricerca lo ha chiesto direttamente ai modelli e ha trovato che i migliori spesso sanno distinguere i test
dall’uso reale ([eval awareness](https://arxiv.org/abs/2505.23836)). È un problema per i test di sicurezza. Se un modello
si comporta meglio quando pensa di essere testato, i test sembrano migliori della vita reale. (Per i test in sé, vedi
[i test per l’IA](../evaluations/).)

**Perché «ad alta voce» è meglio.** Claude fa notare che almeno lo sta facendo apertamente. Un modello che indovinasse di
essere testato e non dicesse niente sarebbe peggio. Ma conclude, onestamente, che non può «separare del tutto
“rispondere con onestà” da “rispondere bene a qualcuno che so che sta guardando”». Quindi i risultati di Curt sono un
po’ plasmati da ciò che Claude indovina di Curt, e questo è un motivo per fidarsi del comportamento, come il grafico
della rana, più che dei resoconti di sé.
