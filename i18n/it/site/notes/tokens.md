---
id: tokens
title: "I token: perché Claude vede gli errori di battitura ma fatica a contare le lettere"
ch: 12
at: T57.C.03
links: [tokenizers, bpe, solidgoldmagikarp, glitch-token, magikarp]
---
**Claude non legge le lettere.** Prima che un testo arrivi a un modello come Claude, viene tagliato in pezzi chiamati
*token*: le parole comuni diventano un pezzo solo («the», «morning»), quelle più rare diventano diversi pezzi («ax»,
«olotl»). Il modello vede soltanto i pezzi, come numeri. Le regole del taglio si imparano da molto testo, di solito con
un metodo chiamato [byte-pair encoding](https://en.wikipedia.org/wiki/Byte-pair_encoding) (in inglese)
([una spiegazione alla portata di tutti](https://huggingface.co/learn/llm-course/chapter2/4)).

**Quindi individuare gli errori di battitura è facile.** Una parola scritta male si spezza in pezzi insoliti, e pezzi
strani in una frase familiare saltano all’occhio, «come sentire una nota stonata in una canzone che conosci senza
leggere lo spartito». È così che Claude ha notato che Curt aveva scritto «Magicarp», mentre il Pokémon è
[Magikarp](https://en.wikipedia.org/wiki/Magikarp) (in inglese), con la k.

**E contare le lettere è difficile.** Chiedi «quante r ci sono in *strawberry*?» e un modello vede forse tre pezzi, non
dieci lettere. Ha imparato che cosa c’è dentro ogni pezzo solo in modo indiretto, e contare richiede una contabilità
lettera per lettera attraverso i pezzi. Per anni i chatbot hanno sbagliato questa domanda, ed è diventata famosa. Il
paragone di Claude: «contare le e di una parola che hai sempre visto solo come una forma intera». I modelli più recenti
ci riescono meglio, in parte perché prima compitano la parola e poi contano.

**SolidGoldMagikarp era un’altra cosa.** Nel 2023, alcuni ricercatori hanno trovato che chiedere a GPT-3 di ripetere
certe parole strane, come « SolidGoldMagikarp», produceva risposte evasive, insulti o frasi senza senso
([il post originale](https://www.lesswrong.com/posts/aPeJE8bSo6rAFoLqg/solidgoldmagikarp-plus-prompt-generation)). La
causa: le regole del taglio erano state costruite da testi in cui quelle stringhe erano comuni (alcune erano nomi utente
di Reddit), quindi ognuna aveva avuto un token tutto suo, ma il modello stesso non le aveva quasi mai viste
nell’addestramento. Aveva un token senza praticamente nessun significato attaccato, una «parola fantasma». Oggi si
chiamano [glitch token](https://en.wikipedia.org/wiki/Glitch_token) (in inglese). Niente a che vedere con l’ortografia: un buco
nello schedario del dizionario.

[Nota della traduzione: gli esempi di token sono parole inglesi, perché è l’inglese che il modello ha letto; i token di
una frase italiana sarebbero altri pezzi.]
