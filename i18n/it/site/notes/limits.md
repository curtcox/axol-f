---
id: limits
title: "Sette limiti dell’IA, molto al di qua della fisica"
ch: 12
at: T60.C.03
links: [landauer, lyapunov, chaos-theory, p-vs-np, scaling-laws, machines-loving-grace, halting-problem, godel, game-theory, margolus-levitin, bekenstein, limits-of-computation]
---
**La domanda di Curt.** Quali limiti potrebbero mettere un tetto alle capacità dell’IA, al di qua del
[limite di Landauer](https://it.wikipedia.org/wiki/Principio_di_Landauer)? (Landauer dimostrò che cancellare un bit di
informazione deve liberare un minimo piccolissimo di calore. È un pavimento reale al costo del calcolo, ma così basso
che «non è particolarmente limitante».) Claude ne dà sette.

1. **Il caos.** In un sistema [caotico](https://it.wikipedia.org/wiki/Teoria_del_caos), piccolissimi errori in ciò che misuri
   crescono in modo esponenziale, l’«effetto farfalla». Quanto avanti puoi prevedere cresce solo con il *logaritmo* della
   tua precisione: t ≈ (1/λ)·ln(Δ/δ), dove λ dice quanto in fretta crescono gli errori
   ([tempo di Lyapunov](https://it.wikipedia.org/wiki/Tempo_di_Ljapunov)). Misura un milione di volte meglio e guadagni solo
   una manciata di «tempi di Lyapunov» in più. È per questo che le previsioni del tempo svaniscono dopo una o due
   settimane, e perché «il meteo, i mercati e le persone restano in parte opachi per qualunque intelligenza».
2. **La complessità.** Alcuni problemi diventano esponenzialmente più difficili man mano che crescono. La maggior parte
   dei matematici crede che nessun metodo ingegnoso li renda facili ([P contro NP](https://it.wikipedia.org/wiki/Classi_di_complessit%C3%A0_P_e_NP)).
   L’intelligenza trova scorciatoie migliori, «ma i casi peggiori restano i peggiori».
3. **Le leggi di scala.** L’IA migliora con più potenza di calcolo, ma lungo una curva dolce: l’errore scende più o meno
   come il calcolo elevato a una piccola potenza negativa ([scaling laws](https://arxiv.org/abs/2001.08361)). Non c’è un
   muro, ma ogni gradino in su costa molte volte di più.
4. **I dati e l’orologio del mondo.** Non si può imparare ciò che non è nei dati, e gli esperimenti (sperimentazioni
   cliniche, raccolti, economie) «vanno alla velocità del mondo, non a quella di chi pensa». Il CEO di Anthropic, Dario
   Amodei, sostiene qualcosa di simile in [*Machines of Loving Grace*](https://darioamodei.com/essay/machines-of-loving-grace).
5. **L’incomputabilità.** Ci sono domande a cui nessun programma può sempre rispondere, come se un programma qualunque
   finirà ([il problema della fermata](https://it.wikipedia.org/wiki/Problema_della_terminazione)), e verità che nessun sistema di
   dimostrazione può raggiungere ([Gödel](https://it.wikipedia.org/wiki/Teoremi_di_incompletezza_di_G%C3%B6del)).
   Valgono anche per l’IA, «anche se in pratica si fanno sentire di rado».
6. **Gli avversari.** Contro altri giocatori capaci di adattarsi, comprese altre IA, i vantaggi si erodono: la
   [teoria dei giochi](https://it.wikipedia.org/wiki/Teoria_dei_giochi) limita ciò che l’intelletto puro può vincere.
7. **La fisica oltre Landauer.** L’energia limita quanto in fretta qualunque sistema può calcolare
   ([Margolus–Levitin](https://en.wikipedia.org/wiki/Margolus%E2%80%93Levitin_theorem) (in inglese)), lo spazio limita quanto può
   contenere ([Bekenstein](https://en.wikipedia.org/wiki/Bekenstein_bound) (in inglese)), e i ritardi dovuti alla velocità della luce
   limitano il coordinamento a distanza ([limiti del calcolo](https://en.wikipedia.org/wiki/Limits_of_computation) (in inglese)).
   «Sono molto larghi, ma reali.»

**La scommessa di Claude.** Il caos e l’orologio del mondo contano di più. «Essere intelligenti non rende prevedibile il
futuro né più veloci gli esperimenti, quindi la capacità probabilmente si assesta su “scommesse molto buone” più che
sull’onniscienza.» La replica di Curt riguarda quanto in alto potrebbero arrivare quelle scommesse (vedi
[il migliore essere umano in tutto](../human-variation/)).
