# Deep Learning 2025/26

Questo repository raccoglie il lavoro svolto per lo sviluppo di modelli di computer vision basati su YOLO per il rilevamento di oggetti in immagini, con un focus su due classi principali: `ball` e `npr`.

## Obiettivo del progetto

L'obiettivo del lavoro è progettare, addestrare e confrontare modelli di object detection in grado di:

- individuare automaticamente oggetti di interesse nelle immagini;
- valutare la qualità dei modelli su dataset custom;
- confrontare diverse configurazioni di training e tuning per migliorare precisione e robustezza;
- costruire una base di lavoro riutilizzabile per ulteriori esperimenti di deep learning.

In pratica, il progetto combina preparazione dei dati, training di reti YOLO, analisi dei risultati e confronto tra versioni del modello.

## Cosa è stato fatto

Nel repository sono stati organizzati i seguenti passaggi principali:

- raccolta e organizzazione dei dataset di addestramento e di test;
- preparazione dei dati in formato compatibile con YOLO e definizione delle classi da rilevare;
- addestramento di più versioni del modello per le classi `ball` e `npr`;
- confronto tra configurazioni differenti per identificare la soluzione migliore;
- salvataggio dei pesi dei modelli migliori e dei risultati ottenuti;
- documentazione dei test e delle esperienze tramite notebook e cartelle di output.

## Struttura del repository

- `datasets/` : dataset usati per l'addestramento e la valutazione.
- `yolo_ball/` : esperimenti e risultati relativi alla classe `ball`.
- `yolo_npr/` : esperimenti e risultati relativi alla classe `npr`.
- `our_new_models/` : modelli finali/ottimizzati prodotti nel corso del lavoro.
- `github_old_models/` : versioni precedenti o baselines di confronto.
- `confronts/` : file e risultati dedicati al confronto tra modelli.
- `yolo_training_ball.ipynb` e `yolo_training_npr.ipynb` : notebook di training e analisi per i due casi.

## Risultati ottenuti

Il lavoro ha permesso di:

- costruire pipeline di training YOLO per due classi distinte;
- realizzare più iterazioni di ottimizzazione del modello;
- analizzare differenze tra versioni e scegliere i pesi più performanti;
- preparare un repository organizzato che documenta il percorso di sviluppo.

In particolare, la cartella `our_new_models` contiene i pesi considerati migliori, mentre le cartelle `yolo_ball` e `yolo_npr` conservano i diversi esperimenti e la relativa documentazione dei risultati.

## Collaboratori

- Matteo — [GitHub](https://github.com/MatteoKova)
- Samuele — [GitHub](https://github.com/sazmb)

## Note

Questo progetto è stato sviluppato nell'ambito del corso di Deep Learning e rappresenta un'esperienza pratica di object detection con reti YOLO, dalla preparazione dei dati all'analisi comparativa dei modelli.
