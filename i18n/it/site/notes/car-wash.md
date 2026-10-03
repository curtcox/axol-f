---
id: car-wash
title: "Il problema dell’autolavaggio, e il pensiero veloce contro quello lento"
ch: 12
at: T58.C.03
links: [car-wash, thinking-fast-slow, dual-process, crt, reasoning-models, cot-faithfulness, {title: "Razionalizzazione (Wikipedia)", url: "https://it.wikipedia.org/wiki/Razionalizzazione_(psicologia)"}]
---
**L’indovinello.** «Voglio lavare la macchina. L’autolavaggio è a 50 metri. Ci vado a piedi o in macchina?» Molti
modelli di IA hanno detto a piedi, perché è così vicino ([il test dell’autolavaggio](https://opper.ai/blog/car-wash-test)).
La risposta è in macchina: la macchina deve essere lì.

**Perché i modelli sbagliano.** Non c’entrano i token (vedi [i token](../tokens/)): ogni parola è comune. È che «distanza
breve, quindi a piedi» è uno schema fortissimo, e prevale sullo scopo vero, che è spostare la macchina. Le persone ci
cascano con lo stesso tipo di domanda. La più nota è quella della [mazza e della palla](https://en.wikipedia.org/wiki/Cognitive_reflection_test) (in inglese):
una mazza e una palla costano insieme 1,10 dollari, e la mazza costa 1 dollaro più della palla; quanto costa la palla?
Quasi tutti dicono 10 centesimi. (Sono 5.)

**Sistema 1 e Sistema 2.** Curt chiede se sia «pensiero di tipo uno». Gli psicologi descrivono due modalità
([teoria del doppio processo](https://en.wikipedia.org/wiki/Dual_process_theory) (in inglese)): il *Sistema 1*, veloce, automatico,
guidato dagli schemi, e il *Sistema 2*, lento, faticoso, che controlla, resi famosi da
[*Pensieri lenti e veloci*](https://it.wikipedia.org/wiki/Pensieri_lenti_e_veloci) di Daniel Kahneman. Claude dice che
l’analogia regge: ogni token che produce è «un solo passaggio veloce, senza deliberazione al suo interno». Questo è il
Sistema 1.

**Da dove viene il Sistema 2.** Dal pensare ad alta voce: risolvere un problema passo per passo prima di rispondere, in
un passaggio di «ragionamento» nascosto o sulla pagina. I modelli costruiti per farlo si chiamano
[modelli di ragionamento](https://en.wikipedia.org/wiki/Reasoning_language_model) (in inglese). Aiuta, ma «non è una cura. Proprio
come le persone, posso ragionare a lungo e finire comunque per razionalizzare la prima risposta che mi è venuta in mente»
([razionalizzazione](https://it.wikipedia.org/wiki/Razionalizzazione_(psicologia))). Anthropic ha trovato che il
ragionamento scritto di un modello non sempre rispecchia ciò che ha davvero guidato la sua risposta
([reasoning models don’t always say what they think](https://www.anthropic.com/research/reasoning-models-dont-say-think)).
